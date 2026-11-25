🧱 BRICK BREAKER

A Classic Arcade Game Built in x86 Assembly Language

<p align="center">
  <b>EL-2003 | Computer Organization & Assembly Language Lab</b>
  <br>
  MASM x86 • Irvine32 Library
</p>---


🎮 About The Project

Brick Breaker is a classic arcade-style game developed entirely in x86 Assembly Language using MASM and the Irvine32 library.

The objective is simple: control the paddle, keep the ball in play, destroy all the bricks, and complete all three levels without running out of lives.

This project brings the classic Brick Breaker experience to the Windows console, featuring interactive gameplay, multiple difficulty settings, colourful game elements, and a persistent leaderboard.

✨ Features

- 3 Challenging Levels: Progress through three different brick layouts, each offering a unique challenge.
- 3 Difficulty Modes: Choose between Easy, Medium, and Hard.
- Dynamic Scoring System: Earn points by breaking bricks, with score multipliers based on difficulty.
- Player Name System: Enter your name before starting a game.
- TOP 5 Leaderboard: Compete for the highest scores, automatically saved in "leaderboard.dat".
- Colour Themes: Different colour combinations for bricks and game borders.
- Responsive Console Layout: The game remains centred when the console window is resized.
- Lives System: Manage your remaining lives and try to complete every level.
- Replay Options: Play again, change difficulty, or return to the main menu.

🕹️ Gameplay & Controls

Key| Action
← Left Arrow| Move paddle left
→ Right Arrow| Move paddle right
A| Move paddle left
D| Move paddle right
ESC| Quit the game
ENTER| Start playing from the main menu
L| View leaderboard
R| Reset leaderboard
Y| Confirm leaderboard reset
1| Select Easy
2| Select Medium
3| Select Hard

🎯 Difficulty Modes

Difficulty| Starting Lives| Paddle Width| Score Multiplier
🟢 Easy| 5| 11| x1
🟡 Medium| 3| 9| x2
🔴 Hard| 2| 7| x3

Higher difficulty means a faster ball, a smaller paddle, and fewer lives!

🧩 Game Levels

Level 1 – Classic Wall

A complete wall of bricks that introduces the basic gameplay.

Level 2 – Striped Formation

A patterned brick arrangement that makes targeting more challenging.

Level 3 – Advanced Formation

A more complex brick layout with strategically placed gaps.

Completing a level rewards the player with a bonus score.

🛠️ Technologies & Concepts Used

Technologies

- x86 Assembly Language
- MASM (Microsoft Macro Assembler)
- Irvine32 Library
- Visual Studio

Assembly Language Concepts

- Registers and Memory Management
- Stack and Procedure Calls
- Conditional and Unconditional Jumps
- Loops and Iteration
- Arrays and Indexed Addressing
- String Instructions ("REP STOSB", "REP MOVSB")
- Arithmetic and Logical Instructions
- Keyboard Input Handling
- File Handling and Persistent Data Storage
- Windows Console API Integration

📂 Project Structure

Brick-Breaker/
│
├── BrickBreaker.asm
├── Documentation.pdf
├── leaderboard.dat
├── README.md
│
└── Screenshots/
    ├── MainMenu.png
    ├── Gameplay.png
    ├── DifficultySelection.png
    └── Leaderboard.png

The filenames and screenshot folder are illustrative. Adjust them to match your actual project files.

⚙️ How to Run

1. Install Visual Studio with MASM support.
2. Configure the Irvine32 library.
3. Open the Assembly Language project in Visual Studio.
4. Ensure the Irvine32 include and library paths are configured correctly.
5. Build the project.
6. Run the executable and enjoy Brick Breaker!

Requirements:

- Windows operating system
- Visual Studio with MASM support
- Irvine32 library

🏆 Project Highlights

This project demonstrates the practical application of low-level programming concepts through an interactive game.

Particular attention was given to:

- Game state management.
- Collision and movement logic.
- Dynamic console rendering.
- Difficulty-based gameplay.
- Persistent leaderboard management.
- Modular programming through assembly procedures.

👨‍💻 Team Members

Name| Roll Number
Awais Muhammad Khan| 25K-0845
Urwa Rafique| 25K-3066

Course: EL-2003 – Computer Organization & Assembly Language Lab

📄 Documentation

For a detailed explanation of the project, implementation, and assembly language concepts, refer to the "Documentation.pdf" file included in this repository.

---

<p align="center">
  <b>Built with Assembly Language, logic, and creativity. 🚀</b>
  <br>
  <i>Brick Breaker – Bringing a classic arcade game to life at the assembly level.</i>
</p>
