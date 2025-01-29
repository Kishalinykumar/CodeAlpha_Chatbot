# CodeAlpha_Chatbot
A Python-based chatbot that simulates human conversation using natural language processing.

# Chatbot using Python and NLTK

## Overview
This is a simple chatbot built using Python and the NLTK library. The chatbot responds to user inputs based on predefined patterns and responses. It provides basic interactions and can handle simple greetings, queries about its purpose, and farewell messages.

## Features
- Recognizes and responds to common greetings.
- Answers basic questions about its identity and purpose.
- Provides a default response for unrecognized inputs.
- Uses pattern matching with predefined responses.
- Runs in a command-line interface.

## Prerequisites
- Python 3.x
- NLTK library

## Installation
1. Install Python 3 if not already installed.
2. Install the required NLTK package using pip:
   ```bash
   pip install nltk
   ```
3. Run the script to download necessary NLTK data:
   ```python
   import nltk
   nltk.download("punkt")
   ```

## Running the Chatbot
1. Save the script as `chatbot.py`.
2. Open a terminal or command prompt.
3. Navigate to the directory where `chatbot.py` is located.
4. Run the script using the command:
   ```bash
   python chatbot.py
   ```
5. Start chatting by typing messages. Type `bye` or `exit` to end the conversation.

## Example Conversation
```
Chatbot: Hello! Type 'bye' to exit the chat.
You: Hi
Chatbot: Hello! How can I assist you today?
You: What is your name?
Chatbot: My name is Chatbot, your virtual assistant!
You: What is your purpose?
Chatbot: I am here to assist you with your questions.
You: Bye
Chatbot: Goodbye! Have a nice day!
```

## License
This project is open-source and free to use.

## Author
Created by [Kishaliny K]


