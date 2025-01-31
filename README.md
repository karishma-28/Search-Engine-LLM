# Search-Engine-LLM

# LangChain - Chat with Search

This project demonstrates a simple chatbot built using **LangChain** and **Streamlit**. The chatbot integrates search tools like **DuckDuckGo**, **Arxiv**, and **Wikipedia** to answer user queries by searching the web. The app uses **LangChain**'s agent framework to handle dynamic interactions and provide accurate responses based on external data sources.

## Features

- **Search Integration**: Uses DuckDuckGo, Arxiv, and Wikipedia for retrieving relevant information.
- **Interactive Chat**: Real-time chat with an AI assistant using **Streamlit** for a seamless user interface.
- **Groq API Integration**: Chatbot responses are powered by Groq's Llama3-8b-8192 model.

## Installation

### Prerequisites

- Python 3.x
- Streamlit
- LangChain
- dotenv (for environment variables)
- Groq API Key

### Steps to Install

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/LangChain-Streamlit-Chat.git
2. Navigate to the project directory:
   ```bash
   cd LangChain-Streamlit-Chat
3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
4. Create a .env file and add your Groq API Key:
   ```bash
   GROQ_API_KEY=your_groq_api_key

**Usage**

Start the Streamlit app:
    ```bash
    streamlit run app.py

**Dependencies**

streamlit: For building the interactive web interface.
langchain: For integrating LangChain's agent and tools.
dotenv: To load environment variables.
groq: For Groq API integration.
