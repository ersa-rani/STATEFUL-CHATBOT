# 🤖 Stateful Chatbot with Chainlit & Gemini API

This is a **stateful chatbot** built using [Chainlit](https://github.com/Chainlit/chainlit) and Google’s Gemini API. The chatbot maintains conversation history and provides context-aware responses.

---

## 🚀 Features
- 🔄 **Stateful Conversations**: Maintains chat history across messages.
- 🔐 **OAuth Authentication**: Supports GitHub authentication.
- ⚡ **Powered by Gemini API**: Uses `gemini-2.0-flash` for AI responses.
- 🛠️ **Built with Chainlit**: Simplifies chatbot development.

---

## 🏗️ Setup & Installation

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/ersa-rani/STATEFUL-CHATBOT.git
cd chatbot-authentication
```

### 2️⃣ Install Dependencies
```bash
pip install -r requirements.txt
```

### 3️⃣ Set Up Environment Variables
Create a `.env` file and add your **Gemini API Key**:
```env
GEMINI_API_KEY=your_api_key_here
```

### 4️⃣ Run the Chatbot
```bash
chainlit run main.py
```

---

## 📜 How It Works

### ✅ OAuth Authentication
- The bot integrates **GitHub OAuth** to authenticate users.
- Once authenticated, the chatbot starts a session.

### 💬 Stateful Chat Handling
- **Session-based History**: The bot stores past messages in `cl.user_session`.
- **Context-aware Responses**: Messages are formatted and sent to the **Gemini API** for intelligent replies.

### 🔧 Main Components
- `oauth_callback`: Handles GitHub authentication.
- `handle_chat_start`: Initializes a new chat session.
- `handle_message`: Manages incoming messages, updates history, and generates responses.

---

## 📷 Demo
![DEMO](https://github.com/user-attachments/assets/8a3e5042-7d47-4078-aa21-36ea80ec721f)


---

## 🛠️ Technologies Used
- Python 🐍
- Chainlit 🔗
- Google Gemini AI 🤖
- OAuth Authentication 🔐
- dotenv 🌱 (for environment variables)

---

## 🤝 Contributing
1. Fork the repository 🍴
2. Create a new branch 🛤️
3. Commit your changes 🎯
4. Push to your branch 🚀
5. Submit a Pull Request 🔥

---

## 📜 License
This project is licensed under the **MIT License**.

---

## 📞 Contact
For any queries or suggestions, reach out at: [your-email@example.com](mailto:ersarani955@gmail.com)

