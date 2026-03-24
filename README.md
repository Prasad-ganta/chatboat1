Context Aware Chatbot
About the Project

This project is a simple chatbot built using Flask and an AI API. The main idea is to create a chatbot that can handle conversations like a customer support assistant.

Instead of replying randomly, the chatbot is designed to understand the user’s message and give meaningful responses. It also supports basic multi-turn conversations, so the user can ask follow-up questions.

Why I Built This

In real customer support systems, users don’t ask everything in one message. They ask step by step. So I wanted to build a chatbot that can handle that kind of conversation.

This project helped me understand how frontend and backend communicate and how APIs are used to generate responses.

Features
Chat interface where user can send messages
Backend API to process messages
AI based responses
Basic conversation flow
Handles errors properly
Technologies Used

Frontend: HTML, CSS, JavaScript
Backend: Python (Flask)
API: Groq AI model

How It Works
User types a message in the input box
JavaScript sends that message to the backend
Flask receives the request
Backend sends the message to the AI API
AI generates a response
Response is sent back to frontend
Chat UI updates with the reply
Project Structure

chatbot-project/

app.py
requirements.txt

templates/
index.html

static/
style.css
script.js

Running the Project

First install dependencies:

pip install -r requirements.txt

Then set your API key:

GROQ_API_KEY=your_api_key

Run the app:

python app.py

Open in browser:

http://127.0.0.1:5000

Example Conversation

User: Hi
Bot: Hello, how can I help you

User: My order is delayed
Bot: Can you share your order ID

User: 12345
Bot: Your order is out for delivery

Limitations

Right now the chatbot does not store long conversation history.
It also depends completely on the API for responses.

Future Improvements
Add chat history storage
Improve UI
Add login system
Better intent handling
Final Thoughts

This project is a basic implementation of a chatbot but it shows how real applications work with frontend, backend, and APIs together.

Author

Prasad Ganta
