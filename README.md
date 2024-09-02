![image](https://github.com/user-attachments/assets/7b5ce066-d11b-4ba6-8ee6-ecdfff679bb2)


**Gemini LLM Application Using RAG**

### This project is a simple Streamlit web application that integrates Google's Gemini Pro model using the google.generativeai library. Users can interact with the large language model (LLM) by asking questions and receiving real-time responses from the Gemini model, with conversation history maintained during the session.

## Features
Interactive Q&A: Users can input questions and receive answers from the Gemini Pro model.
Real-time Streaming: Responses are streamed in real-time as they are generated.
Session State: Chat history is maintained throughout the session.

Environment Variables: API keys and other sensitive data are handled securely using a .env file.

## Requirements

The following Python libraries:
### 1) dotenv : Loading Environment Variables: The line load_dotenv() loads environment variables from a .env file into your program’s environment. This is typically used at the start of the program.

### 2) streamlit : Streamlit simplifies web development by allowing you to create apps using pure Python

### 3) google.generativeai :The google.generativeai library is useful for integrating Google's Gemini language model, enabling you to interact with state-of-the-art large language models (LLMs) directly in your applications. Here’s how google.generativeai can be helpful in your model:
