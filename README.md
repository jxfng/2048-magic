
[English](README.md) | [简体中文](README.zh-CN.md)

# 🎮 2048++

An enhanced version of the classic 2048 game, now with even more fun features! This is a little project I whipped up in my spare time—hope it brings you some joy!

## 🎯 Game Intro

2048 is a simple yet addictive number-merging game. On a 4x4 grid, swipe up, down, left, or right to merge tiles with the same number. The goal? Reach 2048 (but hey, you can keep going for even higher scores)!

**How to play:**
- Use arrow keys or WASD to move the tiles.
- When two tiles with the same number collide, they merge into one.
- After each move, a new 2 or 4 will randomly appear in an empty spot.
- The game ends when there are no more moves left.

## ✨ Special Features

### 1. Undo Function
- Made a wrong move? No worries!
- Just hit the "Undo" button to go back one step.
- You can undo as many times as you like, all the way back to the start.
- Never let a slip of the finger ruin your game again!

### 2. Secret Cheat Mode
- Enter the magic sequence: ←←→→ →→←← (left, left, right, right,  right, right, left, left)
- All tiles will magically turn into 128!
- It’s an Easter egg, just for fun.
- Pro tip: Cheating is fun, but don’t overdo it! 😉

## 🎯 Demo

🎯 Play here: [http:/None/](http://#/)
![image](https://github.com/user-attachments/assets/d4fffe43-f970-4ce0-910e-a984d47f9353)


## 📁 Project Structure
```
2048/
├── static/
│ ├── css/
│ │ └── styles.css # Game styles
│ └── js/
│ └── script.js # Frontend game logic
├── index.html # Main game page
└── 2048.py # Backend server
```
**File Descriptions:**
- `2048.py`: Backend server written with Flask, handles game logic and API requests.
- `script.js`: Frontend game logic, including moves, animations, and special features.
- `styles.css`: Game styles, making sure everything looks nice and responsive.
- `index.html`: The main page that brings everything together.

## 🚀 Getting Started

**Method 1: Download Release**
1. Download the latest release.
2. Make sure you have Python 3.x installed.
3. Install dependencies: `pip install flask`
4. Run: `python 2048.py`
5. Open your browser and go to: [http://localhost:9969](http://localhost:9969)

**Method 2: Clone from GitHub**
```bash
git clone https://github.com/sz30/2048.git
cd 2048
pip install flask
python 2048.py
```

## 🎨 Customization

Want to make it your own? Tweak `styles.css` for a new look, or dive into `script.js` to change up the gameplay. All code is well-commented for easy hacking!

## 📝 License

GPL-2.0 license

## 🤝 Contributing

Still updating! Issues and Pull Requests are super welcome—let’s make this game even more awesome together!


## 🙏 Acknowledgements

Thanks to the following sponsors for supporting this project:

---
_Last updated: May 2025_
