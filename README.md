
# LLM-Powered Chatbot Tutorial 🧠💬

This repository provides a comprehensive example of building a **language model-powered chatbot** that leverages **LangChain** to hold conversations and remember past interactions. It’s designed as an educational resource for beginners and a foundation for advanced chatbot applications, such as:

- **Conversational Retrieval-Augmented Generation (RAG):** Enable chatbots to reference external data.
- **Agent-based Systems:** Create bots that can perform specific actions dynamically.

### Features
- **Dynamic Conversation**: Implements a chatbot using the Groq language model with personalized prompts.
- **LangChain Message History**: Tracks conversation context using LangChain’s `ChatMessageHistory` class, enabling stateful interactions.
- **Token Management**: Configured with a maximum token limit of **70** for responses, ensuring concise and efficient outputs.
- **Prompt Integration**: Uses parameterized prompts to dynamically shape chatbot responses based on user input.

### Prerequisites
- **Python 3.11+**
- **Groq API Key**: Obtain your API key from [Groq](https://groq.com).
- **Dependencies**: Install required libraries such as `langchain`, `dotenv`, and `langchain_groq`.

### How to Use
1. Clone the repository.
2. Set up your environment:
   - Install dependencies using `pip install -r requirements.txt`.
   - Add your Groq API key to a `.env` file.
3. Run the Jupyter Notebook:
   - Configure the chatbot with a token limit of 70 and prompts for dynamic conversation handling.
   - Explore how LangChain’s message history retains context across interactions.

### Code Highlights
- **Prompt Design**: Demonstrates the use of parameterized prompts to tailor responses dynamically.
- **LangChain Integration**: Leverages `ChatMessageHistory` for managing session data and maintaining state.
- **Token Configuration**: Limits responses to 70 tokens for concise outputs, ensuring relevance and efficiency.
- **Reusable Patterns**: Includes functions for session management and history retrieval, enabling scalability.

### Future Enhancements
- Expand with **Conversational RAG** for document-based queries.
- Integrate additional tools to handle user requests dynamically.
- Deploy as a REST service or integrate into an existing web application.
