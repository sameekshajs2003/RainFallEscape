# RainFall Escape

RainFall Escape is a fun and engaging game where players navigate their character through a rainstorm, avoiding raindrops or using an umbrella for protection. The game has two modes: "Use Umbrella" and "Run!!!".
## Description

RainFall Escape is built using Python and Pygame. Players can choose between two game modes:

1. **Use Umbrella**: Protect yourself from raindrops by using an umbrella. Gain points for every raindrop you avoid.
2. **Run!!!**: Navigate through the rainstorm by running and avoid getting hit by the raindrops.

The game ends either when the player collides with a raindrop (in "Run!!!" mode) or when the time runs out (in "Use Umbrella" mode).

# 🌧️ RainFall Escape
<p align="center">
  <img src="https://github.com/user-attachments/assets/3e503769-99a7-4d63-923d-5cad98926c85"
       alt="RainFall Escape Screenshot"
       width="300" />
</p>

Welcome to **RainFall Escape** — a small, cozy Pygame project where you dodge raindrops (or use an umbrella!) and try to beat your best score. 🎮☔

---

## ✨ Preview

- Two modes: **Use Umbrella** (time-based scoring) and **Run!!!** (collision ends the game).
- Controls: Arrow keys to move, Enter to restart, and `Q` to return to the menu.

---

## 🚀 Quick Start (Windows - cmd)

1. Make sure you have Python 3.8+ installed. Verify with:

```cmd
python --version
```

2. (Recommended) Create and activate a virtual environment:

```cmd
python -m venv venv
venv\Scripts\activate
```

3. Install the dependency (Pygame):

```cmd
pip install pygame
```

4. Run the game:

```cmd
python rainfallescape.py
```

---

## 🎮 Controls

- Arrow Keys: Move the player
- Enter: Restart after Game Over
- Q: Return to Main Menu
- Close window or press the window close button to exit

---

## 🧩 Notes & Troubleshooting

- If you get an error like `pygame.error: Couldn't open ...` the image file is missing or misnamed — place the image in the same directory as `rainfallescape.py`.
- If the game opens a tiny or huge window, check `WIDTH` and `HEIGHT` at the top of `rainfallescape.py`.
- If you prefer a `requirements.txt` file, create one with:

```text
pygame
```

and install with `pip install -r requirements.txt`.

---

## 🛠️ Development Tips

- Edit the constants at the top of `rainfallescape.py` to change `WIDTH`, `HEIGHT`, `FPS`, and `GAME_DURATION`.
- Add more raindrops in the `for _ in range(10):` loop if you want harder gameplay.


Enjoy the game — stay dry! ☂️
