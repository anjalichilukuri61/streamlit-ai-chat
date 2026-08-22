# 🤖 Streamlit AI Chat

A simple AI chatbot application built using **Python, Streamlit, and the Groq API**.  
Users can enter questions through a chat interface and receive AI-generated responses.

## 🚀 Features

- 💬 Interactive chat interface
- 🤖 AI-generated responses using Groq API
- ⚡ Fast response generation
- 🔐 Secure API key management using environment variables
- 🎨 Simple and clean Streamlit UI

## 🛠️ Technologies Used

- Python
- Streamlit
- Groq API
- python-dotenv

## 📁 Project Structure

```text
streamlit-ai-chat/
│
├── app.py
├── requirements.txt
├── .gitignore
└── README.md
⚙️ How It Works
User
  ↓
Streamlit Chat Interface
  ↓
Python Application
  ↓
Groq API
  ↓
AI Generated Response
  ↓
Display Response
🔑 Setup
1. Clone the repository
git clone https://github.com/anjalichilukuri61/streamlit-ai-chat.git
2. Navigate to the project
cd streamlit-ai-chat
3. Install dependencies
pip install -r requirements.txt
4. Create a .env file

Create a .env file in the project directory:

GROQ_API_KEY=your_groq_api_key

Replace your_groq_api_key with your actual Groq API key.

Important: Never upload your API key to GitHub.

5. Run the application
streamlit run app.py

The application will open in your browser.

💬 Usage
Start the Streamlit application.
Enter a question in the chat box.
The application sends the question to the Groq API.
Groq generates an AI response.
The response is displayed in the chat interface.
🔐 Environment Variable
Variable	Description
GROQ_API_KEY	API key used to access the Groq API
📦 Dependencies

The project uses the following Python packages:

streamlit
groq
python-dotenv

Install them with:

pip install -r requirements.txt
🎯 Project Purpose

This project demonstrates how to build a simple AI-powered web application using Python and Streamlit and integrate it with an external Large Language Model API.

🔮 Future Improvements
Add chat history
Add streaming responses
Add support for multiple AI models
Add a clear-chat option
Add conversation export
Improve the UI
Add user authentication
