# 📝 Todo Summary Assistant

A full-stack web application that lets users manage their todos, generate a smart summary using an AI model (OpenAI ), and automatically send that summary to a Slack channel via webhook integration.

---

## 🚀 Features

- ✅ Add, edit, and delete todos
- 🤖 Summarize todos using OpenAI or Cohere API
- 📤 Send summary to a Slack channel via webhook
- 💬 Show Slack status (success/failure) in UI
---

## 🛠️ Tech Stack

| Layer       | Technology Used               |
|-------------|-------------------------------|
| Frontend    | React (Create React App)      |
| Backend     | Node.js + Express             |
| Database    | Supabase                      |
| AI API      | OpenAI (or Cohere)            |
| Integration | Slack Webhook                 |

---

## 📁 Project Structure
todo-summary-assistant/
├── mytodoapp-frontend/           
│   ├── public/                   
│   ├── src/                      
│   │   ├── components/           
│   │   ├── pages/                
│   │   ├── App.jsx               
│   │   └── index.js          
│   ├── .env.example             
│   └── package.json             
│
├── mytodoapp-backend/          
│   ├── routes/                  
│   ├── controllers/            
│   ├── services/                
│   ├── utils/                   
│   ├── .env.example             
│   ├── index.js                 
│   └── package.json             
│
├── README.md                    
├── .gitignore                   
└── LICENSE                      






