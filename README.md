# Text to SQL Query Retrieval

## Overview

This project utilizes the Google Gemini Pro LLM model to transform natural language queries into SQL queries, enabling users to retrieve data from a SQLite database interactively through a Streamlit web application.

## Technology Stack

- **Google Gemini Pro LLM**
- **Python**
- **SQLite**
- **Streamlit**

## Features

- Transforms natural language queries into SQL queries
- Retrieves data in real-time from a SQLite database
- Interactive web interface for query input and result display
- Error handling for invalid queries and database issues

## Usage

1. **Input Natural Language Query**: Users input a query in natural language.
2. **Conversion to SQL**: The query is processed and converted into an SQL query using the Google Gemini Pro LLM model.
3. **Database Query Execution**: The SQL query is executed against a SQLite database.
4. **Result Display**: The results are presented in the Streamlit web application.
