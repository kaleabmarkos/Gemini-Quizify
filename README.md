"# Gemini-Quizify" 

## Overview
The Quiz Builder Application is an interactive tool that allows users to generate quizzes based on the content of uploaded PDF documents. Leveraging Streamlit for the user interface and LangChain for natural language processing, this application provides a seamless experience for creating, navigating, and answering quiz questions.

## Features
- **PDF Document Upload**: Users can upload multiple PDF documents, which are processed to extract text content.
- **Quiz Generation**: Based on the extracted content, the application generates quiz questions on a specified topic.
- **Multiple-Choice Questions**: Each quiz question includes multiple choice answers, along with feedback on user responses.
- **Navigation**: Users can navigate through questions and receive explanations for the correct answers.
- **Responsive Design**: The application is built using Streamlit, ensuring a user-friendly interface.

## Technologies Used
- **Python**: The primary programming language for the application.
- **Streamlit**: A framework for building interactive web applications.
- **LangChain**: A library for connecting language models and processing text.
- **Google Cloud Vertex AI**: Used for generating text embeddings for natural language processing.
- **ChromaDB**: A vector store for efficient storage and retrieval of document embeddings.

## Requirements
- Python 3.8 or higher
- Streamlit
- LangChain
- Google Cloud SDK (for authentication with Vertex AI)
- Other dependencies specified in `requirements.txt`

## Installation
1. Clone the repository:
   ```bash
   Fork it
   git clone https://github.com/yourusername/gemini-quizify.git
   cd gemini-quiziify
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   pip install -r requirements.txt
   export GOOGLE_APPLICATION_CREDENTIALS="/path/to/your/credentials.json"
   streamlit run app.py
2, Project Structure:
   ```bash
    gemini-quizify/
    │
    ├── app.py                     # Main application file
    ├── requirements.txt           # List of Python dependencies
    ├── tasks/
    │   ├── task_3.py              # Document processing logic
    │   ├── task_4.py              # Embedding client for Google Vertex AI
    │   ├── task_5.py              # Chroma collection creator
    |   ├── task_6.py
    |   ├── task_7.py
    │   ├── task_8.py              # Quiz generator logic
    │   ├── task_9.py              # Quiz manager for navigation
    |   ├── task_10.py
    │
    └── README.md                  # This README file
   ```
This README file provides a comprehensive overview of the project, making it easier for users and contributors to understand its purpose, how to use it, and how to contribute.
