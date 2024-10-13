# AI-based-Chatbot-using-Langchain
A chatbot made using mainly Streamlit and Langchain.

This repository contains a conversational chatbot built using the [LangChain](https://github.com/hwchase17/langchain) framework, designed to handle a variety of natural language processing (NLP) tasks efficiently.

## Features

- **Conversational AI**: The chatbot leverages LangChain to handle dynamic, multi-turn conversations with a memory-augmented model.
- **Customizable Chain**: Easily modify or extend the chain logic to integrate different models, databases, or workflows.
- **Pre-built Language Models**: Supports various language models like OpenAI GPT, allowing for high-quality text generation.
- **Retrieval-Augmented Generation (RAG)**: The chatbot can perform RAG-style interactions, pulling information from external knowledge sources (e.g., Pinecone, Elasticsearch).
- **OpenAI Integration**: Seamlessly integrates with OpenAI's language models for flexible and intelligent responses.
- **Tool Support**: Can utilize external APIs or tools (like search engines or knowledge bases) to enhance conversation.

## Technologies Used

- **LangChain**: Core library that enables chain-based workflows for NLP applications.
- **OpenAI GPT API**: For advanced language understanding and generation.
- **Pinecone/FAISS/Elasticsearch** (Optional): Retrieval-based augmentation for improved response relevance.
- **Python**: Core programming language used for chatbot logic.
- **Streamlit** : For deploying a user-friendly interface for the chatbot.

![image](https://github.com/user-attachments/assets/64c065ec-c13c-4933-9336-39221a7ee7d2)


## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/langchain-chatbot.git
   cd langchain-chatbot
   ```

2. Install required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Set up environment variables for API keys (e.g., OpenAI API, Pinecone):
   ```bash
   export OPENAI_API_KEY=your-openai-api-key
   ```

4. Run the chatbot:
   ```bash
   streamlit run main.py
   ```

![image](https://github.com/user-attachments/assets/ee873614-131b-4738-84d5-d8027934b451)


## Customization

You can modify the chatbot's behavior by editing the chain logic within the `chatbot.py` file. Some areas for customization include:

- Changing the language model.
- Modifying how the chatbot handles memory or retrieval.
- Adding new tools or APIs to expand capabilities.

## Usage

Once the chatbot is up and running, you can interact with it via the terminal or through a web interface (if integrated with Streamlit). The chatbot is designed to:

- Hold meaningful, multi-turn conversations.
- Fetch relevant information when prompted.
- Assist with tasks such as question answering, summarization, and more.

## Future Enhancements

- **Improved Memory Handling**: Implementing long-term memory to track context over extended sessions.
- **Fine-Tuning**: Training on custom datasets to improve domain-specific performance.
- **Expanded Tool Integration**: Adding more external APIs for enhanced conversational capabilities.

## Contribution

Feel free to open issues or pull requests if you'd like to contribute to improving the chatbot!!
