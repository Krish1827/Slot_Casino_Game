# 🎰 Slot Casino Game

A command-line slot casino game built with Go (Golang). Players can place bets, spin the slots, and track their balance as they play.

## Features

- Player name input
- Slot machine spins with randomized outcomes
- Betting and balance management
- Win and lose mechanics
- Option to quit the game at any time

## Built With

- Go (Golang)
- Go standard library

## Getting Started

### Prerequisites

Install [Go](https://go.dev/dl/) before running the application.

Verify your installation:

```bash
go version
```

### Installation

Clone the repository:

```bash
git clone https://github.com/YOUR-USERNAME/slot-casino-game.git
```

Navigate to the project directory:

```bash
cd slot-casino-game
```

Run the game:

```bash
go run .
```

## How to Play

1. Launch the game in your terminal.
2. Enter your name.
3. Enter your bet amount when prompted.
4. Spin the slots and see the outcome.
5. Track your balance as you play.
6. Enter `0` when prompted to quit.

## Project Structure

```text
slot-casino-game/
├── go.mod
├── main.go
├── spin.go
├── utils.go
└── README.md
```

- **`go.mod`** — Defines the Go module and project dependencies.
- **`main.go`** — Contains the main function and game flow.
- **`spin.go`** — Handles slot machine spinning logic.
- **`utils.go`** — Contains utility and helper functions.
- **`README.md`** — Provides project documentation and instructions.

## Concepts Practiced

- Variables and data types
- Functions and return values
- Loops and conditional statements
- User input and output
- Error handling
- Random number generation
- Basic game logic

## Disclaimer

This project is for educational purposes only. It simulates a casino slot machine and does not involve real-money gambling.
