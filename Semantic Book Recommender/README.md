# Semantic Book Recommender with LLMs

This project aims to build a Semantic Book Recommender, an AI powered system designed to suggest books based on the semantic meaning and emotional tone of user queries. By leveraging advanced Natural Language Processing (NLP) techniques and Large Language Models (LLMs), the system moves beyond simple keyword matching to understand the deeper context and sentiment in both book descriptions and user inputs

<img width="1448" alt="Image" src="https://github.com/user-attachments/assets/1eae284e-01ae-4b71-b015-a7862a531593" />

### Features

* **Semantic Search with Vector Embeddings**: Book descriptions are transformed into vector representations, enabling similarity-based search that captures meaning rather than just keywords.
* **Zero-Shot Text Classification**: Books are categorized as "fiction" or "nonfiction" using LLMs without the need for labeled training data.
* **Emotion and Sentiment Analysis**: Extracts emotional cues from text to help users find books that match a desired emotional tone or mood.
* **Interactive Web Interface**: A Gradio-based application provides an intuitive dashboard for users to receive personalized book recommendations in real time.

---

#### Notebooks

1. `book_rec.ipnb`:
   - Text data cleaning: Preprocess and clean raw book description data for better analysis and model performance.
2. `vector_search.ipynb`:
   - Semantic Vector Search: Building a vector database that allows users to find the most similar books to a natural language query.
3. `text_classification.ipynb`:
   - Text Classification with Zero-Shot Learning: Use LLMs to classify books as "fiction" or "nonfiction" without traditional training data.
4. `sentiment_analysis.ipynb`:
   - Interactive Web Application: Create a user-friendly Gradio dashboard for live book recommendations based on input queries

---

#### Installation
1. Install required Python libraries:
   ```
   pip install -r requirements.txt
2. Clone the Repository:
   ```
   git clone --filter=blob:none --sparse https://github.com/ivanmu-1/python-portfolio.git
   cd python-portfolio
   git sparse-checkout init --cone
   git sparse-checkout set Semantic Book Recommender
4. Set Up a virtual Environment:
   ```
   python -m venv venv
   source venv/bin/activate  # On Windows use: venv\Scripts\activate
5. Run the Gradio Dashboard:
   ```
   gradio_bashboard.py
---

#### How It Works

1. **Download the [Book Dataset](https://www.kaggle.com/datasets/dylanjcastillo/7k-books-with-metadata)**  
   - Load a curated dataset of book titles and descriptions from Kaggle.
2. **Preprocess Text Data**  
   - Clean, normalize, and tokenize descriptions for consistent input to models.
3. **Generate Embeddings**  
   - Use a transformer-based model (e.g., HuggingFace Transformers) to convert book descriptions into semantic vector embeddings.
4. **Process User Queries**  
   - When a user inputs a query, it is embedded and compared against the book vectors using cosine similarity.
5. **Zero-Shot Classification**  
   - LLMs are used to automatically assign genre and emotion categories to books without any labeled training data, enhancing recommendation relevance and diversity.
6. **Classify and Filter**  
   - The top matches are optionally filtered or refined using genre and emotion outputs from zero-shot classification and sentiment analysis.
7. **Display Results**  
   - Recommendations are presented in the Gradio UI with titles, genres, and sentiment tags.

