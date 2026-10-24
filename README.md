# Aptitude Quiz Web Application

## About the Project

The Aptitude Quiz Web Application is a web-based platform designed to help students practice aptitude questions and improve their problem-solving skills. It provides an interactive quiz experience with different categories, a timer, progress tracking, and instant results.

## Features

* Interactive and user-friendly dashboard.
* Multiple quiz categories.
* Quantitative Aptitude, Logical Reasoning, and Verbal Ability.
* Multiple-choice questions with answer options.
* Timer for quiz practice.
* Question progress tracking.
* Instant score calculation and results.
* Answer review after completing a quiz.
* MongoDB database integration for storing quiz questions.
* Responsive and attractive user interface.

## Technologies Used

* **Frontend:** React.js, Vite, HTML, CSS, JavaScript
* **Backend:** Node.js, Express.js
* **Database:** MongoDB
* **ODM:** Mongoose
* **Icons:** Lucide React

## Project Structure

```text
aptitude-quiz-web-app/
├── client/
│   └── src/
│       ├── App.jsx
│       ├── main.jsx
│       └── styles.css
├── server/
│   └── src/
│       ├── data/
│       ├── models/
│       ├── routes/
│       ├── index.js
│       └── seed.js
├── README.md
└── .gitignore
```

## Installation and Setup

### 1. Clone the Repository

```bash
git clone YOUR_REPOSITORY_URL
cd aptitude-quiz-web-app
```

### 2. Start the Backend

```bash
cd server
npm install
```

Create a `.env` file in the `server` folder and configure your MongoDB connection string and server port using the settings specified in `.env.example`.

Seed the database:

```bash
npm run seed
```

Start the backend:

```bash
npm run dev
```

### 3. Start the Frontend

Open a new terminal:

```bash
cd client
npm install
npm run dev
```

Open the local URL displayed in the terminal to use the application.

## Learning Outcomes

* Developed a full-stack web application using the MERN stack.
* Gained experience in React component development.
* Implemented REST API integration using Express.js.
* Integrated MongoDB for data storage.
* Practiced interactive quiz design, timer functionality, and score calculation.

## Future Enhancements

* User registration and login.
* User profiles and quiz history.
* Leaderboard and performance analytics.
* Difficulty-based question selection.
* Admin panel for managing questions.

## Author

Sakshi Shinde
