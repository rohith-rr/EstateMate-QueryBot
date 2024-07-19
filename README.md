
# Conversational Data Retrieval on Real Estate Database



## Table of Contents
1. [Introduction](#introduction)
2. [Installation](#installation)
3. [Usage](#usage)
4. [Results](#results)
5. [Conclusion](#conclusion)

## Introduction

This project is an end-to-end conversational real estate database retrieval system using Streamlit UI, Google Palm LLM, and the Langchain framework. This system provides a user-friendly interface for querying real estate data conversationally. It interacts with a MySQL database for dynamic Q&A, utilizing few-shot learning and Hugging Face embeddings stored in ChromaDB to enhance query accuracy and relevance. Google Palm LLM handles natural language understanding, while Langchain manages the conversational flow.

## Installation

To set up this project, follow these steps:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/conversational-real-estate-retrieval.git
   cd conversational-real-estate-retrieval
   
   ```
2. **Install the required dependencies:**
    use a virtual environment if required
   ```bash
   pip install -r requirements.txt
   ```
3. **Set up the database:**
  Ensure you have a MySQL database set up with your real estate data.
  You can import data using the sql file provided.
## Usage

1. **Start the Streamlit UI:**
   ```bash
   streamlit run app.py
   ```
2. **Enter your query in english**
## Results

The conversational system successfully retrieves and responds to queries about real estate data with high accuracy. Key features include:

- **Natural language understanding** powered by Google Palm LLM.
- **Conversational management** using Langchain.
- **Enhanced query accuracy** with few-shot learning.
## Conclusion

This project demonstrates the integration of advanced AI technologies to create a dynamic and interactive real estate query system. The combination of Google Palm LLM, Langchain, and Hugging Face embeddings offers a robust solution for conversational data retrieval.




