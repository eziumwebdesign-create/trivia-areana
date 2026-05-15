# TriviaArena

A real-time multiplayer browser trivia game supporting up to 10 players per room, with live scoring and a speed bonus system.

Built with **JavaScript · WebSockets · Node.js**

---

## Features

- Multiplayer lobby — up to 10 players per room
- 15 trivia questions across CS, Web Dev, Algorithms, and more
- 10 second timer per question
- Speed bonus points for fast correct answers
- Live scoreboard that updates after every question
- Podium and final leaderboard at the end
- Play again without refreshing

---

## How to Play

1. Open `index.html` in your browser
2. Enter your name and click **Join Game**
3. Wait for other players to join the lobby
4. Click **Start Game** when ready
5. Answer each question before the timer runs out
6. Faster correct answers earn bonus points
7. Highest score after 10 questions wins

---

## Scoring

| Action | Points |
|--------|--------|
| Correct answer | 100 pts |
| Speed bonus (max) | +50 pts |
| Wrong answer | 0 pts |
| Time up | 0 pts |

---

## Tech Stack

- **Frontend**: HTML, CSS, Vanilla JavaScript
- **Multiplayer**: WebSocket simulation (Node.js + ws for production)
- **Deployment**: Any static host (GitHub Pages, Netlify, Render)

---

## Running the Production Version

For real multiplayer with WebSockets:

```bash
npm install
node server.js
```

Then open `http://localhost:3000` in multiple browser tabs to test multiplayer.

---

## Screenshots

> Add a screenshot of your running game here

---

## Author

Alex Johnson · [LinkedIn](https://linkedin.com/in/your-profile) · [GitHub](https://github.com/your-username)
