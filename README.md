# Ping Pong Game (Assembly)

🏓 **Ping Pong Game** is a **two-player console-based game written in Assembly language**, featuring **real-time ball movement, paddles, scoring, and difficulty levels**. Built with easy-to-understand assembly logic, it's great for beginners learning low-level programming.

## 🌟 Features

- 🏆 **Two-Player Mode** – Compete against a friend.
- 🎮 **Smooth Ball & Paddle Movement**
- 🔄 **Scoring System** – First to 5 points wins!
- ⏸️ **Pause & Resume Gameplay**
- ⚡ **Difficulty Modes** – Normal & Hard levels

## 🛠️ Technologies Used

- **Assembly (x86, 16-bit NASM)**
- **BIOS Interrupts** – For keyboard input and display
- **Direct Memory Access** – For screen rendering

## 🎮 Controls

- **Player 1:** `W` (Up) | `S` (Down)
- **Player 2:** `↑` (Up) | `↓` (Down)
- **Start:** Press `G`
- **Pause/Resume:** Press `P`
- **Toggle Difficulty:** Press `H`

## 📂 Project Structure

```
PingPongGame/
│── pingPong.asm        # Main source code
│── gameRecdoring.mp4   # Screen recording of game
│── Documentation.xml   # Main documentation
│── assets              # Screenshots of game
│── README.md           # Project documentation
```

## 🚀 How to Run

### **Using DOSBox + NASM (Windows/Linux)**

1. Install **NASM** and **DOSBox**.
2. Assemble the program:
   ```sh
   nasm -f bin pingPong.asm -o pingPong.com
   ```
3. Run it in DOSBox:
   ```sh
   dosbox pingPong.com
   ```

## 📜 License

This project is for educational purposes only. Feel free to modify and improve it

