Before the running the Project 

1. Install this these packages:

    pip install langchain
   langgraph
   langchain-google-genai
   python-dotenv
   google-generativeai

2. Create a Google Gemini API Key and paste it in .env file 

    GOOGLE_API_KEY=


This project is a command-line AI assistant built using LangChain, Google Gemini API, and LangGraph ReAct agents. The assistant can interact with users, perform arithmetic calculations through custom tools, and provide dynamic responses using a tool-calling workflow.

Features
🧠 Uses Google Gemini (gemini-1.5-flash) as the LLM
🔧 Custom tool integration with @tool decorators
➕ Calculator tool for arithmetic operations
👋 Greeting tool for personalized responses
⚡ ReAct-based agent using LangGraph
💬 Interactive command-line chatbot interface
🔄 Streaming responses in real time
Tech Stack
Python
LangChain
LangGraph
Google Gemini API
dotenv
Use Cases
Learning AI agent architecture
Understanding tool calling with LLMs
Exploring LangGraph ReAct workflows
Building AI-powered CLI assistants
