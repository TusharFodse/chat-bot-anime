# 🤖 Chat-Bot Anime | Flask + Groq API

A WhatsApp-style role-based chatbot built with **Flask** and powered by **Groq's LLaMA 3 model**.

---

## 🔥 Features

- Choose your anime bot (Naruto, Gojo, Luffy, or custom)
- Role-based login with email and role selection
- Chat UI inspired by WhatsApp
- Intelligent responses using **Groq's LLaMA 3 70B** via API
- Fully coded by **Tushar Fodse**

---

## 💻 Technologies Used

- 🐍 Python + Flask
- 🌐 HTML, CSS, JavaScript
- 🤖 Groq API (LLaMA 3)
- 🛠 Dotenv, Flask session
- ⚙️ Custom chatbot logic

---

## 🚀 How to Run Locally

```bash
git clone https://github.com/TusharFodse/chat-bot-anime.git
cd chat-bot-anime

# Create virtual environment
python -m venv venv
venv\Scripts\activate        # Windows
# OR
source venv/bin/activate     # Mac/Linux

# Install dependencies
pip install -r requirements.txt

# Add your Groq API key in .env file
# Example:
# key=your_groq_api_key
# SECRET_KEY=any_secret

python app.py
