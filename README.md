C.A.L.M (Conversational AI with Language Models)

Project Overview

C.A.L.M is a Streamlit-based web application that leverages Google's Gemini model to provide conversational AI capabilities. It allows users to input questions and receive real-time responses while maintaining a chat history. The app is designed to be interactive and user-friendly, with a sidebar for quick navigation through the chat history.

Features

Real-time Responses: Utilizes Google's Gemini AI model for conversational responses.

Streamlit Integration: Provides an intuitive interface for users to interact with the chatbot.

Chat History: Maintains a session-based history of user queries and bot responses.

Sidebar Navigation: Displays chat history as clickable titles for easy access.

Technologies Used

Python

Streamlit

Google Generative AI SDK

dotenv (for secure API key management)

Prerequisites

Python 3.7 or higher

Google API key (with access to the Gemini model)

Installation and Setup

Clone the Repository:

git clone https://github.com/your-repo/calm.git
cd calm

Install Dependencies:

pip install -r requirements.txt

Set Up Environment Variables:

Create a .env file in the project root.

Add your Google API key:

GOOGLE_API_KEY=your_api_key_here

Run the Application:

streamlit run app.py

How to Use

Open the application in your browser (default URL: http://localhost:8501).

Enter your question in the input field and click the "Ask the question" button.

View the AI's response and the complete chat history in the main section.

Use the sidebar to navigate through chat history.

File Structure

app.py: Main application code.

.env: Environment file for API key management.

requirements.txt: List of dependencies.

Future Enhancements

Add support for multiple languages.

Integrate additional AI models for broader use cases.

Enable persistent storage for chat history.

License

This project is licensed under the MIT License.

Acknowledgments

Streamlit for the web app framework.

Google Generative AI for the Gemini model.
