QuizWiz
Overview
QuizWiz is a real-time multiplayer quiz game where players can compete against friends or other players in timed quiz battles. The app features live leaderboards, room-based competition, and interactive gameplay using Node.js, React, and Socket.io.

Features
Real-time multiplayer quiz matches

Timer-based questions with score tracking

Room creation and joining for private games

Live leaderboard updates during matches

Responsive and user-friendly interface

Tech Stack
Frontend: React with Vite

Backend: Node.js with Express

Real-time Communication: Socket.io (WebSockets)

Database: (If any, mention here e.g. MongoDB or none)

Getting Started
Prerequisites
Node.js (v14 or above)

npm or yarn

Installation
Clone the repository:

bash
Copy code
git clone https://github.com/anjalijaiswal04/QuizWiz.git
cd QuizWiz
Install dependencies for backend and frontend:

Backend:

bash
Copy code
cd backend
npm install
Frontend:

bash
Copy code
cd ../frontend
npm install
Running the App
Start backend server:

bash
Copy code
cd backend
npm start
Start frontend development server:

bash
Copy code
cd ../frontend
npm run dev
Open your browser at http://localhost:3000 (or the port your frontend uses).

How to Play
Create or join a quiz room.

Answer each question before the timer runs out.

Scores are updated live.

Compete to top the leaderboard!

Folder Structure
bash
Copy code
QuizWiz/
├── backend/      # Node.js server code
├── frontend/     # React app source code
└── README.md
Contributing
Feel free to fork the repo and submit pull requests. For major changes, please open an issue first.
