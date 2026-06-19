# Rock Paper Scissors Game

A clean, interactive **Rock Paper Scissors** game built with vanilla HTML, CSS, and JavaScript — no frameworks, no dependencies.

##  Live Demo

http://127.0.0.1:5500/index.html
<img width="640" height="316" alt="image" src="https://github.com/user-attachments/assets/89373773-3d68-4cab-9d12-082b844cc0bc" />


##  Preview

The game features three clickable choices — **Rock**, **Paper**, and **Scissors** — with real-time score tracking and instant result feedback.

##  Features

-  Click-to-play interface with image-based choices
-  Random computer move generation
-  Live scoreboard (You vs Computer)
-  Color-coded result messages (green = win, red = loss)
-  Instant replay — just click again

##  Tech Stack

| Technology | Usage |
|------------|-------|
| HTML5 | Game structure & layout |
| CSS3 | Styling, hover effects, responsive design |
| JavaScript (Vanilla) | Game logic, DOM manipulation, event handling |

##  Project Structure

```
rock-paper-scissors/
│
├── index.html      # Main HTML file
├── style.css       # Stylesheet
├── app.js          # Game logic
├── stone.png       # Rock image
├── paper.jpg       # Paper image
└── scissor.jpg     # Scissors image
```

## ⚙️ How to Run Locally

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/your-repo-name.git
   ```

2. **Open the project folder**
   ```bash
   cd your-repo-name
   ```

3. **Open `index.html` in your browser**
   ```bash
   # Simply double-click index.html, or use Live Server in VS Code
   ```

No installation or build step required!

##  Game Rules

| Your Choice | Computer Choice | Result |
|-------------|-----------------|--------|
| Rock | Scissors | ✅ You Win |
| Paper | Rock | ✅ You Win |
| Scissors | Paper | ✅ You Win |
| Same | Same | 🤝 Draw |
| Any | Stronger | ❌ You Lose |

##  How It Works

1. Player clicks one of the three choice buttons
2. Computer randomly picks Rock, Paper, or Scissors
3. `playGame()` compares both choices using game logic
4. Result is displayed with a color-coded message
5. Scores update automatically

##  Author

**Your Name**
- GitHub: [@your-username](https://github.com/your-username)

## 📄 License

This project is open source and available under the [MIT License](LICENSE).
