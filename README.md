# NewsLens – ML-Based News Intelligence System

NewsLens is an intelligent news analysis application that combines Machine Learning, Natural Language Processing (NLP), semantic embeddings and similarity search to analyze and explore news articles.

## Features

- **News Classification:** Classifies news articles into four categories: World, Sports, Business and Sci/Tech.
- **TF-IDF Feature Extraction:** Converts textual news content into numerical features.
- **Logistic Regression:** Performs multiclass news classification.
- **Semantic Embeddings:** Uses Sentence Transformers (`all-MiniLM-L6-v2`) to generate contextual representations of news articles.
- **K-Means Clustering:** Groups contextually similar news articles.
- **Interactive Dashboard:** Provides real-time news classification, prediction confidence, semantic search and news analytics.

## Dataset

**AG News Dataset**
- Training samples: 120,000
- Testing samples: 7,600
- Categories: World, Sports, Business and Sci/Tech

## Tech Stack

- **Programming Language:** Python
- **Machine Learning:** Scikit-learn
- **NLP:** TF-IDF, Sentence Transformers
- **Classification:** Logistic Regression
- **Clustering:** K-Means
- **Dashboard:** Streamlit
- **Data Processing:** Pandas, NumPy

## Project Workflow

1. Load and preprocess the AG News dataset.
2. Extract textual features using TF-IDF.
3. Train a Logistic Regression classifier for news categorization.
4. Generate semantic embeddings using Sentence Transformers.
5. Apply K-Means clustering to group similar articles.
6. Build a FAISS index for semantic similarity retrieval.
7. Integrate the models into an interactive Streamlit dashboard.

## Installation and Setup

1. Clone the repository:

   `git clone YOUR_REPOSITORY_URL`

2. Navigate to the project directory:

   `cd NewsLens`

3. Install dependencies:

   `pip install -r requirements.txt`

4. Run the application:

   `streamlit run app.py`

## Disclaimer

NewsLens is an educational and portfolio project developed for news classification, semantic analysis and information retrieval.
