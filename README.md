# Beamify Chat Microservice

Beamify Chat is a real-time chat microservice designed for the Beamify platform. Built with 
Node.js, WebSocket, MongoDB, and Redis, it provides scalable, low-latency messaging for
live chat, group chat, and platform integrations. The service supports chat relays for Twitch 
and Kick, emoji support, and robust authentication.

## Overview

Beamify Chat enables real-time communication for the Beamify ecosystem, offering:

- Live chat for streams, channels, and groups
- WebSocket-based messaging with low latency
- Integration with Twitch and Kick chat via relays
- Persistent message storage in MongoDB
- Redis for pub/sub and scaling
- JWT-based authentication and user validation

## Key Features

- **Real-Time Messaging:** WebSocket server for instant chat delivery
- **Channel & Group Support:** Multiple chat rooms, channels, and group messaging
- **Third-Party Relays:** Twitch and Kick chat integration (bi-directional relays)
- **Persistence:** MongoDB-backed message storage and retrieval
- **Scalability:** Redis pub/sub for horizontal scaling and distributed chat
- **Authentication:** JWT validation for secure user sessions
- **Emoji & Media:** Emoji support and extensible message payloads
- **REST API:** Endpoints for message history, moderation, and chat management

## Technology Stack

- **Runtime:** Node.js
- **WebSocket:** ws
- **Database:** MongoDB (Mongoose)
- **Cache/Scaling:** Redis
- **Framework:** Express.js
- **Integrations:** tmi.js (Twitch), Kick relay
- **Other:** JWT, dotenv, emoji-mart
