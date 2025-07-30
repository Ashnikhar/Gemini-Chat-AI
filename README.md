
# 💬 Gemini AI Chatbox

A modern fullstack AI-powered chatbox using **Google Gemini Pro API**, built with **React** (frontend) and **Express.js** (backend). Supports smooth, styled interactions with the Gemini LLM.

---

## 🚀 Features

- 🔹 Gemini Pro integration (via API key)
- 💡 Real-time chat interface
- ✨ Clean, modern UI with message bubbles
- 📦 React + Express fullstack setup
- 📜 Easy-to-follow codebase

---

## 📁 Project Structure

```

gemini-chatbox-modern-ui/
├── server/
│   ├── server.js          # Express backend server
│   └── package.json       # Backend dependencies
└── client/
├── public/
│   └── index.html     # Root HTML
├── src/
│   ├── App.js         # Chat logic + UI
│   ├── App.css        # Modern styling
│   └── index.js       # Entry point
└── package.json       # Frontend dependencies

````

---

## 🛠️ Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/gemini-chatbox-modern-ui.git
cd gemini-chatbox-modern-ui
````

### 2. Install Backend

```bash
cd server
npm install
```

Update the API key in `server.js`:

```js
const API_KEY = "YOUR_GEMINI_API_KEY";
```

Start the backend:

```bash
node server.js
```

### 3. Install Frontend

```bash
cd ../client
npm install
npm start
```

> Frontend runs on [http://localhost:3000](http://localhost:3000)
> Backend runs on [http://localhost:5000](http://localhost:5000)



## 🔐 Environment Setup

You can keep the API key hardcoded for quick testing. For production:

1. Store it securely in `.env` file (backend).
2. Never expose the key in frontend code.

---

## 📦 Tech Stack

* **Frontend**: React, CSS
* **Backend**: Node.js, Express
* **AI**: Google Gemini Pro API

---

## 📃 License

This project is licensed under the [MIT License](LICENSE).

---

## 🙌 Acknowledgments

* [Gemini API Documentation](https://ai.google.dev/)
* [Create React App](https://create-react-app.dev/)

```
