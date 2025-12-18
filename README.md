# ChessBot - Browser Version

Play chess against an AI opponent in your browser!

## 🎮 Play Now

**Live Demo:** https://johnkelly22.github.io/Chess-Bot-Demo/

## 🔊 Sound Note

Due to browser security policies, sound will only work after you interact with the page:

- Click anywhere on the page when it first loads
- This enables audio for the rest of your session

## 🤖 AI Features

- Minimax algorithm with alpha-beta pruning
- Adjustable difficulty (depth 4 by default)
- Visual feedback showing "AI Thinking..."
- Move highlighting for both players

## 🎯 How to Play

1. Click on a piece to select it
2. Click on a valid square to move
3. The AI will automatically respond
4. Capture the opponent's king to win!

## 🛠️ Development

Built with:

- Python 3.12
- Pygame
- Pygbag (for web deployment)

### Local Development

```bash
# Run locally
python main.py
```

### Deploy to GitHub Pages

```bash
# Use the deployment script
deploy_to_github.bat
```

This will:

1. Build the web version with pygbag
2. Copy files to the demo repository
3. Push to GitHub Pages

---

Enjoy playing chess! 🎉
