Gemini Pro Chatbot using Streamlit (Python)

This project builds a simple and interactive AI chatbot powered by Google’s Gemini Pro LLM. The app is created using Streamlit, allowing users to have real-time conversations directly from their browser with a clean and user-friendly interface.

Features

Real-time chat with Google Gemini Pro

Clean and modern Streamlit-based UI

Conversation memory using session state

Secure API key handling with .env

Easy to run locally with minimal setup

Project Structure

main.py – Main Streamlit application file

.env – Stores your Google API key (not included in repo)

requirements.txt – List of required Python packages

README.md – Project overview and instructions (this file)

Technologies Used

Python

Streamlit

Google Generative AI (Gemini Pro)

python-dotenv

Virtual environment (recommended)

How It Works

User enters a prompt in the Streamlit chat UI

The app sends the prompt to the Gemini Pro API

Gemini processes the input and returns a response

Streamlit displays the reply in a chat-style format

Session memory keeps track of previous messages

This creates a smooth, ChatGPT-like conversation experience.

How to Run

Clone the repository

Install dependencies:

pip install -r requirements.txt


Create a .env file and add your API key:

GOOGLE_API_KEY=your_api_key_here


Run the app:

streamlit run main.py


Open the browser window and start chatting!

Results

The chatbot successfully responds to user questions in real time

Provides natural, AI-generated text using Gemini Pro

Lightweight and fast — ideal for demos or experimentation
