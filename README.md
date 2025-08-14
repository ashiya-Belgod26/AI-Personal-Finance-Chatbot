Personal Finance Chatbot

This project is a Personal Finance Chatbot designed to help users manage and analyze their finances. It provides natural language understanding (NLU) for financial text, budget summaries, Q&A capabilities, and spending insights. The frontend is built with React and Tailwind CSS for a modern, responsive UI, while the backend uses FastAPI with Hugging Face models for intelligent analysis.

Features

NLU Analysis: Extract financial insights from user text.

Budget Summary: Track income, expenses, savings, and major spending categories.

Q&A: Ask finance-related questions and receive AI-driven answers.

Spending Insights: Identify high spending areas and receive suggestions to optimize finances.

Tech Stack

Frontend: React, Tailwind CSS

Backend: FastAPI, Python

AI: Hugging Face models for NLU and Q&A

Installation
Backend

Create and activate a virtual environment:

python -m venv venv
# Linux/Mac
source venv/bin/activate
# Windows
venv\Scripts\activate


Install dependencies:

pip install fastapi uvicorn python-dotenv requests


Set environment variables in a .env file:

HF_API_KEY=your_huggingface_api_key
HF_GRANITE_MODEL=ibm-granite/granite-3.3-2b-instruct
HF_QA_MODEL=deepset/roberta-base-squad2


Run the backend server:

uvicorn main:app --reload

Frontend

Navigate to the frontend folder:

cd finance-ui


Install dependencies:

npm install


Start the frontend:

npm start

Usage

Access the frontend at http://localhost:3000

Use the chatbot to analyze financial text, track budgets, ask questions, and gain spending insights.

Contributing

Contributions are welcome. Please create issues or pull requests to suggest improvements.

License

This project is licensed under the MIT License.
