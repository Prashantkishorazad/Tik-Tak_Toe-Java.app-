# Tik-Tak_Toe-Java.app-
# 🎮 Tic Tac Toe Game  

A simple yet fun **Tic Tac Toe (X and O)** game built using **HTML**, **CSS**, and **JavaScript**.  
This project demonstrates how front-end web technologies can create interactive and visually appealing browser games.  

---

## 🧠 Project Overview  

The **Tic Tac Toe Game** allows two players to compete in the classic 3x3 grid challenge.  
Players take turns marking their symbol (**O** or **X**) in the boxes.  
The first player to align three symbols horizontally, vertically, or diagonally wins the game.  
If all boxes are filled and no one wins, it results in a **draw**.  

This project is a beginner-friendly JavaScript exercise that focuses on DOM manipulation, event handling, and game logic design.  

---

## 🛠️ Technologies Used  

- **HTML5** → for game structure  
- **CSS3** → for styling, layout, and responsive design  
- **Vanilla JavaScript (ES6)** → for interactivity and game logic  

---

## ⚙️ Features  

1. Two-player gameplay (O and X)  
2. Responsive layout for all screen sizes  
3. Real-time turn switching  
4. Winner detection for 8 possible win patterns  
5. Reset and New Game functionality  
6. Disable boxes after win to prevent further clicks  
7. Clean, user-friendly interface  
8. Lightweight – no external libraries or frameworks  


## 💡 Core Logic Explained  

- **Event Listeners:** Added to all boxes to capture user clicks.  
- **Turn System:** A boolean flag (`turnO`) keeps track of which player’s turn it is.  
- **Win Checking:** The script iterates through all possible winning index patterns.  
- **Winner Display:** Displays a message and disables the grid when a winner is found.  
- **Reset/New Game:** Clears the grid and hides the winner message for a fresh start.

- TicTacToe/
│
├── index.html          # Main HTML structure
├── style.css           # Game styling
├── app.js              # JavaScript logic
└── README.md           # Project documentation







