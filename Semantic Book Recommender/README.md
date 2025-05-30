# Semantic Book Recommender with LLMs

This project aims to build a Semantic Book Recommender, an AI powered system designed to suggest books based on the semantic meaning and emotional tone of user queries. By leveraging advanced Natural Language Processing (NLP) techniques and Large Language Models (LLMs), the system moves beyond simple keyword matching to understand the deeper context and sentiment in both book descriptions and user inputs

### *Features*

* Semantic Search with Vector Embeddings: Book descriptions are transformed into vector representations, enabling similarity-based search that captures meaning rather than just keywords.
* Zero-Shot Text Classification: Books are categorized as "fiction" or "nonfiction" using LLMs without the need for labeled training data.
* Emotion and Sentiment Analysis: Extracts emotional cues from text to help users find books that match a desired emotional tone or mood.
* Interactive Web Interface: A Gradio-based application provides an intuitive dashboard for users to receive personalized book recommendations in real time.

#### *Notebooks*

1. `book_rec.ipnb`:
   - Text data cleaning: Preprocess and clean raw book description data for better analysis and model performance.
2. `vector_search.ipynb`:
   - Semantic Vector Search: Learn how to build a vector database that allows users to find the most similar books to a natural language query.
3. `text_classification.ipynb`:
   - Text Classification with Zero-Shot Learning: Use LLMs to classify books as "fiction" or "nonfiction" without traditional training data.
4. `sentiment_analysis.ipynb`:
   - Interactive Web Application: Create a user-friendly Gradio dashboard for live book recommendations based on input queries

