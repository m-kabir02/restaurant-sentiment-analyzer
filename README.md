# 🍽️ Restaurant Review Sentiment Analyzer
Building a full-stack, RESTful web application designed to showcase the power of Natural Language Processing (NLP) and full-stack development. This app will provide a platform for users to submit, manage, and analyze restaurant reviews.

## 🚀 Features
- **RESTful API with CRUD**: The core of the application is a robust API that handles all data operations, including Create, Read, Update, and Delete reviews. This allows for a flexible and scalable architecture.
- **Hugging Face** Integration: Leverages a pre-trained Hugging Face Transformer model (RoBERTa) to perform state-of-the-art sentiment analysis on each review. The model classifies reviews into sentiment categories (positive, negative, neutral) with a corresponding confidence score.
- Relational Database: All reviews and their sentiment analysis results are stored in a relational database for persistent, scalable data management.
- Interactive Dashboard (Planned): The project will feature a frontend interface that displays sentiment analysis results in a clear, interactive dashboard, visualizing the distribution of sentiments across all reviews.


## 🛠️ Tech Stack
- Python: The primary programming language.
- Flask: A micro-framework for building the RESTful API.
- Hugging Face transformers: For sentiment analysis.
- SQLAlchemy: An Object-Relational Mapper (ORM) to handle all database interactions and CRUD operations.

## 📈 Database
- SQL (PostgreSQL): A powerful, open-source relational database for storing review data.

## Frontend:
Streamlit: For the initial interactive dashboard.
