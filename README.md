# SigmaGPT

SigmaGPT is a full-stack AI chat application built with React, Node.js, Express, MongoDB, and the OpenAI API.

It is a ChatGPT-inspired application where users can chat with an AI assistant, create multiple conversations, and manage their previous chats through a simple interface.

## Live Demo

https://sigmagpt-frontend-c9fk.onrender.com/

## Features

- AI-powered chat using the OpenAI API
- Create and manage multiple conversations
- Save and view previous chat history
- Delete conversations
- Markdown support for AI responses
- Code syntax highlighting
- Typing effect for AI responses
- Dark and light mode
- MongoDB-based conversation storage

## Tech Stack

### Frontend

- React
- Vite
- CSS
- React Markdown
- Highlight.js

### Backend

- Node.js
- Express.js
- MongoDB
- Mongoose
- OpenAI API

## How It Works

The React frontend handles the chat interface and user interactions.

When a user sends a message, the frontend communicates with the Node.js and Express backend. The backend sends the request to the OpenAI API and returns the response to the frontend.

Conversation data is stored in MongoDB so previous chats can be accessed and managed later.


## Screenshots

### Chat Interface

![SigmaGPT Chat Interface](./Screenshot%202026-09-22%20163728.png)

### Chat History

![SigmaGPT Chat History](./Screenshot%202026-09-22%20163755.png)
