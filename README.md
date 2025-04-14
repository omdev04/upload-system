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

---

### 🚀 Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/Om976346/upload-system.git
   ```

2. **Navigate into the project folder:**

   ```bash
   cd upload-system
   ```

3. **Install dependencies:**

   ```bash
   pip install -r requirements.txt
   ```

4. **Set environment variables:**  
   Create a `.env` file in the root directory with the following content:

   ```
   TELEGRAM_BOT_TOKEN=your_telegram_bot_token
   TELEGRAM_CHAT_ID=@your_channel_username_or_chat_id
   ```

5. **Run the Flask server:**

   ```bash
   python app.py
   ```

6. **Open your browser and go to:**

   ```
   http://localhost:5000
   ```

---

## 🗂 File Structure

```
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
```

---

## 📸 Screenshots

> Add screenshots of the UI and Telegram bot below:

**Upload Interface:**

![Screenshot 1](Screenshots/2.png)

**Telegram Bot Receiving Files:**

![Screenshot 2](Screenshots/3.png)

---

## 🧪 Usage

- Open the web page in your browser  
- Select a file using the upload form  
- Click **Upload**  
- The file will be sent to your Telegram channel via bot  

---

## 🤝 Contributing

Contributions are welcome!  
Feel free to fork the repo, suggest features, open issues, or submit pull requests.

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---

## 👤 Author

**Om**  
🔗 [GitHub Profile](https://github.com/Om976346)
```

---

Let me know if you’d like me to also help you generate:
- `.env` template file
- `requirements.txt`
- Live deployment guide (e.g., Render, Railway, Heroku, etc.)
