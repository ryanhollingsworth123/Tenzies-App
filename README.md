# Tenzies-App

**A small Tenzies game built with React and Vite for learning purposes.**  
This project demonstrates how to build an interactive dice-matching game using React hooks and component state.

---

## Live Demo

Check out the live demo here:  
https://ryanhollingsworth123.github.io/Tenzies-App/

---

## What is Tenzies?

Tenzies is a simple dice game where the goal is to get *all* the dice to show the same number.  
Each turn, you roll ten dice — clicking a die will “hold” it so it doesn’t reroll. Keep rolling until all dice match!

---

## How to Play

1. Click **Roll** to roll all dice.
2. Click on any die you’d like to hold.
3. Continue rolling until *all* ten dice show the same value.
4. Win when all dice match!

---

## Tech Stack

- **React** – UI & game logic  
- **Vite** – Dev server + build tool  
- **JavaScript**, **JSX** – Components & state  
- **CSS** – Basic styling  
- **npm** – Dependency management

---

## Project Structure

Tenzies-App/
├── public/ # Static assets + HTML
├── src/ # React source files
│ ├── components/ # Components (e.g., Die.jsx)
│ ├── App.jsx # Main app & game logic
│ └── index.jsx # Entry point
├── .gitignore
├── index.html
├── package.json # Scripts & deps
├── vite.config.js # Vite config
└── README.md

---

## Installation

1. **Clone the repo**

   ```bash
   git clone https://github.com/ryanhollingsworth123/Tenzies-App.git
Install dependencies

cd Tenzies-App
npm install
Run locally

npm run dev
Open your browser:

http://localhost:5173/
