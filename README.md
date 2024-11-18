# Multi-Tool LangChain Agent with Groq-Optimized LLMs and ReAct Framework

This project integrates multiple useful tools into a LangChain-based agent powered by Groq-optimized open-source Large Language Models (LLMs), including Llama3 and Mixtral. The system is designed to handle a variety of queries, ranging from personal database lookups to Wikipedia searches, mathematical calculations, and text summarization. It leverages the efficiency and power of Groq's hardware acceleration for executing advanced NLP tasks. The tools included in this project support multiple operations and provide detailed responses to user queries.

The project employs the **Reasoning Action (ReAct)** framework, which combines reasoning and action steps to enhance the agent's capabilities. This framework allows the agent to not only process the input but also determine the appropriate steps and tools to use based on reasoning.

## Features

- **Date Retrieval:** Fetch today's date.
- **Personal Information Lookup:** Query for specific information such as name, age, role, etc.
- **Wikipedia Search:** Search and retrieve summaries from Wikipedia.
- **Math Calculator:** Evaluate mathematical expressions.
- **Text Summarization:** Summarize long texts using a pre-trained transformer model.
- **Python Code Execution:** Execute Python code dynamically within the environment.
  
## Technologies

- **Groq-Optimized LLMs:** Use of Llama3 and Mixtral models to power the agent's decision-making capabilities.
- **LangChain Framework:** A framework for building powerful and flexible agents.
- **Reasoning Action (ReAct) Framework:** A framework for reasoning through tasks and selecting actions based on context and user queries.
- **Python:** The primary language used for coding the agent and integrating with the Groq API.
- **Hugging Face Transformers:** Used for implementing the text summarization functionality.
  
