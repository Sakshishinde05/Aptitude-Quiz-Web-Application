# Aptitude Quiz Web Application

A full-stack single-page aptitude quiz application built with React, Express, Node.js, and MongoDB.

## Features
- Professional responsive dashboard UI
- Quantitative Aptitude, Logical Reasoning, and Verbal Ability categories
- Timed quiz sessions with progress tracking
- Instant score, accuracy, and answer review
- Quiz questions loaded from the Express API (MongoDB when configured, starter questions otherwise)
- MongoDB question seeding script
- Input validation and a simple health endpoint

## Requirements
- Node.js 20+
- MongoDB local installation or a MongoDB Atlas connection string

## Setup

### 1. Backend
```bash
cd server
npm install
```
Copy `.env.example` to `.env` and set `MONGODB_URI`.

Seed starter questions into MongoDB:
```bash
npm run seed
```

Start the backend:
```bash
npm run dev
```
Backend runs at `http://localhost:5000`.

### 2. Frontend
Open a second terminal:
```bash
cd client
npm install
npm run dev
```
Open the Vite URL shown in the terminal (usually `http://localhost:5173`).

## Environment variables
See `server/.env.example`. Never commit your real `.env` file.

## Notes
- The frontend is a single-page application; navigation between dashboard, quiz, and results happens without page reloads.
- If MongoDB is not configured or the database has no questions, the API returns built-in starter questions so you can test the UI.
