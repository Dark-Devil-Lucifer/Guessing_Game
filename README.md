🎯 Rust Guessing Game (CLI)

A simple command-line number guessing game written in Rust. This project is ideal for beginners learning Rust and getting familiar with basic programming concepts such as loops, conditionals, and user input.

---

## 🚀 Features

- Generates a random number between 1 and 100
- Prompts the user to guess the number
- Provides feedback: “Too high!”, “Too low!”, or “You win!”
- Continues until the correct guess is made
- Clean and readable Rust code structure

---

## 🛠️ Getting Started

### ⚙️ Requirements

- Rust and Cargo installed  
  You can install both with [rustup](https://rustup.rs/):
  ```bash
  curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
🔧 Build & Run
bash
Copy
Edit
git clone https://github.com/Dark-Devil-Lucifer/Guessing_Game.git
cd Guessing_Game
cargo run
📁 Project Structure
bash
Copy
Edit
Guessing_Game/
├── src/
│   └── main.rs         # Game logic
├── Cargo.toml          # Rust project config
└── .gitignore          # Git exclusions
📸 Preview
graphql
Copy
Edit
Guess the number!
Please input your guess: 50
Too low!

Please input your guess: 75
Too high!

Please input your guess: 63
You win!
