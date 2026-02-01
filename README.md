## 🤖 Converso AI

Converso AI is a full-stack AI chat application where users can interact with an AI assistant through a modern chat interface. The project uses a React (Vite) frontend and a Node.js + Express backend integrated with the OpenAI API.

## 🚀 Features

- 💬 Interactive AI chat interface  
- 🧠 AI responses powered by OpenAI  
- ⚡ Fast React frontend built with Vite  
- 🔄 Context-based chat handling  
- 🗂 Organized full-stack project structure  
- 🔐 Secure API key handling using environment variables  

## 🛠 Tech Stack
#### Frontend
- React (Vite)
- JavaScript (ES6+)
- CSS

#### Backend
- Node.js
- Express.js
- MongoDB (for chat threads)
- OpenAI API

## 📂 Project Structure
```
Converso-AI/
│
├── Backened/                 # Express backend
│   ├── models/
│   │   └── Thread.js         # MongoDB thread schema
│   │
│   ├── routes/               # API route handlers
│   │
│   ├── utils/
│   │   └── openai.js         # OpenAI integration logic
│   │
│   ├── server.js             # Main Express server
│   ├── server2.js            # Secondary/experimental server
│   ├── package.json
│   ├── package-lock.json
│   └── .env                  # Environment variables (NOT pushed)
│
├── Frontened/                # React frontend
│   ├── public/
│   │   └── vite.svg
│   │
│   ├── src/
│   │   ├── assets/
│   │   │   └── blacklogo.png
│   │   │
│   │   ├── App.jsx
│   │   ├── Chat.jsx
│   │   ├── ChatWindow.jsx
│   │   ├── Sidebar.jsx
│   │   ├── MyContext.jsx     # Global state management
│   │   ├── main.jsx
│   │   └── styles (CSS files)
│   │
│   ├── index.html
│   ├── vite.config.js
│   ├── eslint.config.js
│   ├── package.json
│   ├── package-lock.json
│   └── .gitignore
│
└── .gitignore                # Root gitignore for full project
```

## 1️⃣ Clone the Repository
```bash
git clone https://github.com/rahulagarwal27/Converso-AI
cd Converso AI
```

## 2️⃣ Backend Setup
```bash
cd Backened
npm install
```

## Create a .env file inside Backened:
```
OPENAI_API_KEY=your_api_key_here
MONGO_URI=your_mongodb_connection_string
```

## Start backend server:
```bash
npm start
```


## 3️⃣ Frontend Setup
Open a new terminal:
```bash
cd Frontened
npm install
npm run dev
```


## App runs at:
```
http://localhost:5173
```


## 🔒 Environment Variables
The .env file is required in the backend folder and should contain:
OpenAI API Key
MongoDB connection string

## ⚠️ This file is ignored in GitHub for security.

## 👨‍💻 Author
Rahul Agarwal
Full Stack Developer | AI Enthusiast 🚀

## ⭐ Support
If you like this project, consider giving it a ⭐ on GitHub!











