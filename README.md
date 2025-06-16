## Talyy Your Bot Friend

Talyy AI Chatbot is a smooth conversational AI system that simulates interactions with a real person. The project
combines OpenAI's GPT technology with Redis for persistent conversation history and a modern web interface for user 
experience.

## Features

-🧠 Natural Conversations: AI responses with personality simulation prompt

-💾 Persistent History: Redis Session Management 

-🔄 Session Management: Unique session IDs for each conversation

-⚡ Real-time Interaction: Typing indicators and smooth UI

-🔒 Secure Deployment: Containerized with Docker

-🔧 Easy Configuration: Environment variable based setup

## Prerequisites

- Docker and Docker Compose
- OpenAI API Key
- Git

## Technology Stack

- Backend:	Python, Flask
- AI Engine:	OpenAI GPT-3.5
- Memory Store:	Redis
- Frontend:	HTML5, CSS3, JavaScript
- Containerization:	Docker, Docker Compose

## Getting Started

1. Clone the Repository

2. Set Up Environment Variables

   Create a .env file 

3. Run the Application with Docker Compose

   ```bash
   docker-compose up --build
   ```
   
4. Access the Application

The app will be available at:
👉 http://localhost:5000/chat

## Project Structure

```
├── chatbot.py            # Main Flask application code
├── Dockerfile            # Docker configuration
├── docker-compose.yml    # Docker Compose configuration
├── static/
│   └── index.html        # Frontend HTML file
├── requirements.txt      # Python dependencies
└── README.md             # Project documentation
```

## Environment Variables

- URL: redis://localhost:6379
- OPENAI_API_KEY – Your OpenAI API key

## License
This project is licensed under the terms of the license included in the repository.
Please refer to the LICENSE file for more details.