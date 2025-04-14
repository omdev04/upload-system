# 📁 File Upload System

A web-based file upload system built using **HTML, CSS, JavaScript**, and **Python (Flask)**. This project allows users to upload files via a web interface, which are then sent and stored securely in a **Telegram bot channel** using the **Telegram Bot API**.

---

## ✨ Features

- ✅ Upload files through the browser
- ☁️ Store files directly in a private Telegram channel via bot
- 🔄 View status of uploads
- 🎨 Clean and responsive UI
- 🐍 Backend built with Python Flask
- 🔐 Secure and fast file handling without local storage

---

## 🛠 Tech Stack

- **Frontend:** HTML, CSS, JavaScript
- **Backend:** Python (Flask)
- **Bot Integration:** Telegram Bot API
- **Storage:** Telegram Channel via Bot
- **Server:** Flask (local or cloud hosting)

---

## ⚙️ Getting Started

### ✅ Prerequisites

Make sure you have:

- Python 3.x
- Flask
- A Telegram Bot Token
- A Telegram Channel where the bot is an admin

### 🚀 Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/Om976346/upload-system.git

   Navigate into the project folder:

bash
Copy
Edit
cd upload-system
Install dependencies:

bash
Copy
Edit
pip install -r requirements.txt
Set environment variables:
Create a .env file in the root directory with the following content:

ini
Copy
Edit
TELEGRAM_BOT_TOKEN=your_telegram_bot_token
TELEGRAM_CHAT_ID=@your_channel_username_or_chat_id
Run the Flask server:

bash
Copy
Edit
python app.py
Open your browser and go to:

arduino
Copy
Edit
http://localhost:5000
🗂 File Structure
bash
Copy
Edit
upload-system/
│
├── templates/
│   └── index.html          # Web interface
├── static/
│   ├── style.css           # CSS styles
│   └── script.js           # JavaScript logic
├── app.py                  # Flask backend
├── requirements.txt        # Python dependencies
└── .env                    # Environment variables (not committed)
