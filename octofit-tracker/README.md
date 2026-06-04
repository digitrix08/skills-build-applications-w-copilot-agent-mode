# OctoFit Tracker

A modern multi-tier fitness tracking application built with React 19, Node.js/Express, and MongoDB.

## Architecture

```
octofit-tracker/
├── frontend/          # React 19 + Vite
│   ├── src/
│   ├── package.json
│   └── vite.config.js
└── backend/           # Node.js + Express + TypeScript
    ├── src/
    ├── package.json
    └── tsconfig.json
```

## Services & Ports

- **Frontend**: http://localhost:5173 (React 19 + Vite)
- **Backend API**: http://localhost:8000 (Express)
- **MongoDB**: mongodb://localhost:27017/octofit

## Getting Started

### Frontend Setup

```bash
cd octofit-tracker/frontend
npm install
npm run dev
```

### Backend Setup

```bash
cd octofit-tracker/backend
npm install
cp .env.example .env
npm run dev
```

### Prerequisites

- Node.js (v18+)
- MongoDB (running on port 27017)

## Technology Stack

- **Frontend**: React 19, Vite, CSS
- **Backend**: Node.js, Express, TypeScript
- **Database**: MongoDB with Mongoose ODM
- **Port Configuration**: 5173 (frontend), 8000 (backend), 27017 (MongoDB)

## Project Structure

This is a foundation for building a modern fitness tracking application with a clear separation between frontend and backend services.
