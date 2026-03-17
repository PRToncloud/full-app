# 🚀 Full Stack Learning Project: React + Node.js + Rust

A comprehensive full-stack application for learning modern web development with **React**, **Node.js**, **Rust**, **PostgreSQL**, and **Real-time Features**.

## 📋 Table of Contents
- [Project Structure](#project-structure)
- [Tech Stack](#tech-stack)
- [Quick Start](#quick-start)
- [Learning Path](#learning-path)
- [Features](#features)
- [Deployment](#deployment)

## 🏗️ Project Structure

```
full-app/
├── frontend/                 # React 18+ Application
├── backend/                  # Node.js/Express Server
├── rust-service/            # Rust Microservices (Actix-web)
├── database/                # PostgreSQL Migrations & Seeds
├── docker-compose.yml       # Local Development Setup
└── docs/                    # Documentation
```

## 🛠️ Tech Stack

| Layer | Technology | Purpose |
|-------|-----------|---------|
| **Frontend** | React 18, Vite, TailwindCSS | Modern UI with hooks & state management |
| **Backend** | Node.js, Express, JWT | RESTful APIs, Authentication, Middleware |
| **High-Performance** | Rust, Actix-web | Real-time WebSockets, Heavy Computation |
| **Database** | PostgreSQL, Prisma ORM | Robust relational data with migrations |
| **Real-time** | WebSockets (Node.js + Rust) | Live updates, notifications, chat |
| **DevOps** | Docker, Docker Compose, GitHub Actions | Local dev environment, CI/CD |

## 🚀 Quick Start

### Prerequisites
- Node.js 18+
- Rust 1.70+
- Docker & Docker Compose
- Git

### Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/PRToncloud/full-app.git
   cd full-app
   ```

2. **Start with Docker Compose** (includes PostgreSQL + Redis)
   ```bash
   docker-compose up -d
   ```

3. **Frontend Setup**
   ```bash
   cd frontend
   npm install
   npm run dev
   ```
   Access at: http://localhost:5173

4. **Backend Setup**
   ```bash
   cd ../backend
   npm install
   npm run dev
   ```
   API runs at: http://localhost:3000

5. **Rust Service** (optional for advanced learning)
   ```bash
   cd ../rust-service
   cargo run
   ```
   WebSocket server at: ws://localhost:8080

## 📚 Learning Path

Check `LEARNING_ROADMAP.md` for structured learning milestones:

1. ✅ **Fundamentals** - Project setup, Git, environment config
2. 🔐 **Authentication** - JWT, OAuth, password hashing
3. 💾 **Database** - PostgreSQL, schemas, migrations, queries
4. 🔌 **API Development** - REST endpoints, error handling, validation
5. 📡 **Real-time Features** - WebSockets, live notifications
6. 🦀 **Rust Integration** - Actix-web, async handling
7. 🚀 **Deployment** - Docker, GitHub Actions, hosting

## ✨ Features

- 🔐 User Authentication (JWT + Refresh Tokens)
- 👥 User Profiles & Authorization
- 💬 Real-time Chat/Notifications
- 🗄️ PostgreSQL Database with Migrations
- 🔄 RESTful & WebSocket APIs
- 📱 Responsive UI with TailwindCSS
- ⚡ Rust Microservices for Performance
- 🐳 Docker & Docker Compose Setup
- 🔄 GitHub Actions CI/CD Pipeline
- 📖 Comprehensive Documentation

## 🚀 Deployment

Deployment guides for:
- **Render** - Full stack hosting
- **Railway** - Quick deployment
- **AWS EC2** - Self-managed servers
- **Vercel** - Frontend only

See `docs/DEPLOYMENT.md` for detailed instructions.

## 📖 Documentation

- `LEARNING_ROADMAP.md` - Learning milestones & tasks
- `docs/SETUP.md` - Detailed setup instructions
- `docs/API.md` - API documentation
- `docs/DATABASE.md` - Database schema & migrations
- `docs/DEPLOYMENT.md` - Deployment guides

## 🤝 Contributing

This is a personal learning project. Feel free to fork and customize!

## 📝 License

MIT License - See LICENSE file for details

## 🎯 Learning Goals

By completing this project, you will learn:
- ✅ Full-stack web development
- ✅ User authentication & security
- ✅ Database design & management
- ✅ RESTful & Real-time APIs
- ✅ Frontend frameworks (React)
- ✅ Backend frameworks (Node.js, Rust)
- ✅ DevOps & Deployment
- ✅ Git & GitHub workflows

---

**Started**: 2026-03-17
**Author**: PRToncloud
**Status**: 🚀 In Development