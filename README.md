# real-time-chat-jb
Real-time chat communication app using FastAPI WebSockets + Docker + scalable service architecture.

```
real-time-chat-jb/
│
├── backend/
│   ├── app/
│   │   ├── __init__.py
│   │   ├── main.py                  # FastAPI app with WebSocket endpoint
│   │   ├── models.py                # Optional, if you store users/messages
│   │   ├── schemas.py               # Pydantic models
│   │   ├── utils.py                 # Helper functions (e.g., message formatting)
│   │   └── config.py                # Environment configs
│   │
│   ├── requirements.txt
│   └── Dockerfile
│
├── frontend/
│   ├── src/
│   │   ├── App.jsx
│   │   ├── index.jsx
│   │   ├── components/
│   │   │   └── ChatRoom.jsx
│   │   └── services/
│   │       └── websocket.js         # WebSocket connection logic
│   ├── package.json
│   └── Dockerfile
│
├── docker-compose.yml
└── README.md
```
