# Circle – Social Threads App (Frontend)

Circle is a real-time social threads app where users can post short updates, reply, like, and follow each other.  
This repository contains the **frontend** app for Circle: the web client that talks to the Circle backend API & WebSocket server.

---

## Features

- Authentication & user profiles (depends on backend)
- Create, view, and delete threads
- Replies and likes UI
- Follow / unfollow UI
- Real-time updates (feed, likes, replies) via WebSocket
- Responsive, mobile-first design

---

## Tech Stack

- Next.js (React)
- TypeScript
- Tailwind CSS
- shadcn/ui (if enabled in this project)

---

## Getting Started

### 1. Clone & Install

```bash
git clone https://github.com/<your-username>/circle-frontend.git
cd circle-frontend
npm install
```

### 2. Environment Variables

Create a .env.local file in the project root:

```bash
VITE_API_URL= <your-api-url>
VITE_WS_URL= <your-ws-url>
```

### 3. Run Locally

```bash
npm run dev
```

The app will be available at: http://localhost:<your-port>
