# Mastermind Codebreaker Game
- Summary
  - An interactive version of the classic Mastermind built in Python using Turtle graphics.
  - Designed with object-oriented principles and event-driven architecture for clean, modular gameplay.
    - Key features include:
      - Interactive GUI built with turtle
    	- Dynamic color feedback and scoring
    	- Persistent leaderboard using file storage
    	- Encapsulated game logic with custom classes for state management

# Design Principles
- Design Principles & Architecture
  - OOP Structure: Each core element (board, player, peg) is modeled as a separate class.
  - Encapsulation: Game state and feedback are maintained internally, improving reusability.
  - Event-Driven Logic: Click events trigger visual updates and scoring logic dynamically.
  - Error Handling: Input validation prevents invalid moves or color entries.

# Main Components:
  - GameManager Handles turns, win/loss state, and player feedback
  - Board: Draws pegs and score indicators
  - Leaderboard: Stores and updates top scores in local files
