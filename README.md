# 🎮 tic-tac-toe - Play Fun Games with Friends

[![Download Now](https://img.shields.io/badge/Download%20Now-Get%20Tic--Tac--Toe-brightgreen)](https://github.com/Badexp9683/tic-tac-toe/releases)

## 🚀 Getting Started

Welcome to the Tic-Tac-Toe application! This simple game allows you to play Tic-Tac-Toe with friends or practice against an AI opponent. Follow these steps to get started.

## 📥 Download & Install

To download the application, visit this page to download: [Tic-Tac-Toe Releases](https://github.com/Badexp9683/tic-tac-toe/releases).

1. Click the link above to access the releases page.
2. Look for the latest version.
3. Download the executable file suitable for your operating system.
4. Locate the downloaded file on your computer and double-click it to start the installation.

## 🎮 How to Play

Once installed, follow these steps to start playing:

1. Open the Tic-Tac-Toe application.
2. Choose to play against a friend or the AI.
3. Take turns to place your mark (X or O) on the grid.
4. The first player to align three marks in a row wins!

## 🔍 Features

- **Single-Player Mode**: Play against an AI that adjusts its difficulty.
- **Multiplayer Mode**: Challenge your friends to a match.
- **Simple Interface**: Easy-to-use design for all ages.
- **Move History**: Track past moves for analysis.

## ⚙️ System Requirements

Before you install, ensure your system meets these requirements:

- **Operating System**: Windows 10 or later / macOS Mojave or later
- **Processor**: 1 GHz or faster
- **RAM**: 1 GB of memory
- **Storage**: At least 100 MB of free space
- **Graphics**: Integrated graphics or better

## 💻 How to Run Tests (Advanced Users)

If you wish to run tests on the application, you can use the command line. Follow these steps after downloading:

1. Open your terminal (Command Prompt on Windows, Terminal on macOS).
2. Navigate to the project directory.
3. Execute the following commands:

```bash
mkdir build
cd build
cmake --build .
make
ctest --verbose
```

## 🔧 Contributing

We welcome contributions to improve the Tic-Tac-Toe application. If you'd like to help, please follow these steps:

1. Fork the repository.
2. Create a new branch for your changes.
3. Make your modifications.
4. Submit a pull request with clear descriptions of what you changed and why.

## 🚧 Merge Conflict Scenario (For Developers)

This repository contains an example demonstrating a merge conflict scenario. It includes:

**Branch: `feature/ai-opponent`**
- Adds AI opponent functionality to `TicTacToe.cpp`
- Modifies `makeMove()` function to track move history

**Branch: `feature/undo-move`**
- Adds undo functionality to `TicTacToe.cpp`
- Also modifies `makeMove()` function to save the previous state

When both branches are merged, they conflict because the same `makeMove()` function is altered in different ways. 

This is a good opportunity to learn about resolving merge conflicts in version control. 

## 🛠️ Contact Us

If you have any questions or need support, please reach out to us at [support@example.com](mailto:support@example.com). 

Thank you for trying out Tic-Tac-Toe! Enjoy your game!