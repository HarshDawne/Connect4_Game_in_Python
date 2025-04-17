# Connect4_Game_in_Python
#🎮 Connect 4 – Python Game with Pygame

This is a GUI-based **Connect 4** game built using **Python** and **Pygame**. It supports two players, turn-based gameplay, and real-time win detection (horizontal, vertical, and both diagonal directions). The board updates visually with colored discs for each player.

---

## 🧠 Game Logic

- 6 Rows × 7 Columns board structure
- Players alternate turns dropping a disc into a column
- First player to align 4 of their discs in a row (horizontally, vertically, or diagonally) wins

---

## 🛠️ Tech Stack

- **Language**: Python 3
- **Libraries**: 
  - `numpy` – for board matrix and data handling
  - `pygame` – for graphical interface and event handling
  - `math` and `sys` – for calculations and system interaction

---

## 🎨 Gameplay Features

- Dynamic GUI with colored tokens:
  - 🔴 Player 1 (Red)
  - 🟡 Player 2 (Yellow)
- Mouse-controlled dropper animation
- Instant feedback on valid moves
- Win detection and celebration message
- Auto-close after win message

---

## ▶️ How to Run

1. **Install Requirements**:
   ```bash
   pip install pygame numpy
