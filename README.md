# My LLM Chatbot 🤖

A full-stack AI conversational interface powered by **Flask** and **HuggingFace Transformers**. This project integrates the `facebook/blenderbot-400M-distill` model to provide a real-time, interactive chat experience directly in the browser.

## 🚀 Features
* **AI Engine:** Powered by Blenderbot for natural language processing.
* **Asynchronous Chat:** Uses JavaScript `fetch` API for a smooth, no-reload experience.
* **Persistent History:** Tracks conversation context within the Python backend.
* **Responsive Design:** A custom CSS interface with loading animations and mobile-friendly layouts.

## 🛠️ Tech Stack
* **Backend:** Python, Flask
* **Frontend:** HTML5, CSS3, JavaScript (Vanilla)
* **AI Library:** HuggingFace Transformers, PyTorch
* **Model:** Blenderbot-400M-Distill

## 📂 Project Structure
```text
LLM_application_chatbot/
├── app.py              # Flask server and Model logic
├── static/             # CSS, JavaScript, and Image assets
├── templates/          # HTML interface
├── requirements.txt    # Python dependencies
└── README.md           # Project documentation

⚙️ Setup Instructions
Clone the repository:

git clone [https://github.com/PerinR/LLM_application_chatbot.git](https://github.com/PerinR/LLM_application_chatbot.git)
cd LLM_application_chatbot

Install dependencies:
pip install -r requirements.txt
Run the application:

flask run
Open http://127.0.0.1:5000 in your browser to start chatting!

🧠 Key Learnings
Managed Large Language Model (LLM) context windows and history.

Debugged cross-origin (CORS) and 500 Internal Server Errors.

Implemented professional Git version control and GitHub workflows.

Created with ❤️ by JC (part of IBM Specialization course)
