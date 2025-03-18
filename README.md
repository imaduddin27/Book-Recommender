# BookWise  
### Your Intelligent Book Recommendation System  

Discover your next favorite read with the power of Large Language Models (LLMs). BookWise uses semantic search, sentiment analysis and zero-shot classification to recommend books tailored to your preferences.

---

## Table of Contents
1. [Project Overview](#project-overview)
2. [Components](#components)
3. [Installation](#installation)
4. [Usage](#usage)
5. [Technologies Used](#technologies-used)


---

## Project Overview

This project is a comprehensive guide to building a semantic book recommender system using LLMs. It covers the following key steps:
- Cleaning and preprocessing text data.
- Building a vector database for semantic search.
- Classifying books using zero-shot classification.
- Performing sentiment analysis to extract emotions from text.
- Creating a web application for users to interact with the recommender system.

---

## Components

The project is divided into five main components, each implemented in a separate Jupyter notebook or Python script:

1. **Data Exploration and Cleaning**  
   - Notebook: `data-exploration.ipynb`  
   - Cleans and preprocesses the text data for further analysis.

2. **Semantic Search and Vector Database**  
   - Notebook: `vector-search.ipynb`  
   - Builds a vector database to enable semantic search, allowing users to find books similar to a natural language query (e.g., "a book about a person seeking revenge").

3. **Text Classification**  
   - Notebook: `text-classification.ipynb`  
   - Uses zero-shot classification to classify books as "fiction" or "non-fiction," enabling users to filter books by genre.

4. **Sentiment Analysis**  
   - Notebook: `sentiment-analysis.ipynb`  
   - Performs sentiment analysis to extract emotions from text, allowing users to sort books by tone (e.g., suspenseful, joyful, or sad).

5. **Web Application**  
   - File: `gradio-dashboard.py`  
   - Creates a user-friendly web application using Gradio for book recommendations.

---

## Installation

To set up the project, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/imaduddin27/BookWise.git
   cd BookWise

2. Install the required dependencies:
    ```bash
    pip install -r requirements.txt

3. Create a .env file in the root directory and add your GoogleAPI key:
    ```bash
    GOOGLE_API_KEY=your_api_key_here

4. Download the dataset from Kaggle and place it in the appropriate directory. Follow the instructions in the repository for downloading the data.

---

## Usage

1. Running the Notebooks
    - Open the Jupyter notebooks in the order specified above to explore the data, build the vector database, classify books and perform sentiment analysis.
2. Running the Web Application
    - Execute the Gradio dashboard script to launch the web application:
    ```bash
    python gradio-dashboard.py
    ```
    - Access the application via the provided local URL.

---

## Technologies Used

1. Libraries and Frameworks:
    - pandas, matplotlib, seaborn for data manipulation and visualization.
    - langchain-community, langchain-chroma, transformers for LLM integration and semantic search.
    - gradio for building the web application.
    - python-dotenv for managing environment variables.

2. APIs: Google API for LLM functionalities.





