# Chat with Databases

This Streamlit web app allows users to interact with databases through a conversational interface. The app leverages LangChain, RAG (Retrieval-Augmented Generation), and Groq's API for efficient natural language understanding and database querying.

## Features

- Natural Language Queries: Use natural language to query your database.
- LangChain Integration: Streamlines interaction between the database and the language model.
- RAG (Retrieval-Augmented Generation): Ensures more accurate responses by retrieving relevant information from the database before generating an answer.
- Groq's API: Used to boost performance and speed up retrieval and generation tasks.
- Streamlit Interface: Provides a simple, user-friendly UI for users to chat with databases.

## Requirements

Before running the app, make sure you have the following dependencies installed:

- Python 3.8+
 
You can install the required Python libraries using the following command:

```bash
   pip install -r requirements.txt
```
## Setup

1. Clone this repository:
```bash
   git clone https://github.com/Kaushalvadadoria28/Chat-With-Databases.git
   cd Chat-With-Databases
```

2. Install the dependencies:
```bash
   pip install -r requirements.txt
```

3. Set up your database connection details and API keys in the .env file:
```bash
   DATABASE_URL="https://raw.githubusercontent.com/lerocha/chinook-database/master/ChinookDatabase/DataSources/Chinook_Sqlite.sql"
   GROQ_API_KEY=your_groq_api_key
```

4. Run the app:
```bash
   streamlit run app.py
```

## Usage

Once the app is running, you can interact with the database by typing natural language queries into the chat interface. The app will process your input and retrieve relevant data from the database.

## Key Components

- LangChain: Manages interactions between the user and the database.
- RAG: Improves response accuracy by retrieving context from the database.
- Groq's API: Optimizes query handling and response generation.
- Streamlit: Provides the web interface for the app.

## Future Enhancements

- Support for more databases
- Advanced query analytics
- Better error handling and user feedback

## Contributing

Feel free to contribute by submitting issues or pull requests.
