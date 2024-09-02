# 0x0A. Prime Game

## Overview
This project involves developing an algorithm to determine the winner of a competitive game based on prime numbers and game theory. Maria and Ben play a game with a set of consecutive integers, where they take turns removing prime numbers and their multiples. The player unable to make a move loses the game. The challenge is to simulate multiple rounds of this game and determine the overall winner.

## Concepts Needed
### Prime Numbers:
- **Definition:** A prime number is a natural number greater than 1 that has no positive divisors other than 1 and itself.
- **Algorithms:** Efficient methods to identify prime numbers within a range.
  
### Sieve of Eratosthenes:
- **Purpose:** An efficient algorithm to find all prime numbers up to a given limit.
- **Usefulness:** Helps in identifying primes quickly, which is crucial for this game.

### Game Theory:
- **Basic Principles:** Involves competitive games where players take turns, and understanding strategies that lead to a win or loss.
- **Optimal Play:** Strategies that ensure the best possible outcome for a player.

### Dynamic Programming/Memoization:
- **Concept:** Reusing previously computed results to make future calculations faster.
- **Application:** Optimizing the solution for multiple game rounds.

### Python Programming:
- **Core Concepts:** Loops, conditional statements, arrays, and lists.
- **Use:** Implementing game logic, tracking game state, and applying algorithms.

## Resources
- **Prime Numbers and Sieve of Eratosthenes:**
  - Khan Academy: [Introduction to prime numbers](https://www.khanacademy.org/)
  - Sieve of Eratosthenes in Python: Step-by-step implementation guide.

- **Game Theory Basics:**
  - Introduction to Game Theory: A simple explanation of game theory and strategic decision-making.

- **Dynamic Programming:**
  - What Is Dynamic Programming With Python Examples: An introduction to dynamic programming with Python examples.

- **Python Official Documentation:**
  - Python Lists: Managing lists in Python, useful for tracking the game state.

## Tasks
### 0. Prime Game (mandatory)
- **Objective:** Determine the winner of multiple rounds of the prime number game.
- **Prototype:** `def isWinner(x, nums)`
  - **Parameters:**
    - `x`: Number of rounds.
    - `nums`: List containing `n` for each round.
  - **Return:** Name of the player who won the most rounds or `None` if the winner cannot be determined.

- **Example:**
  ```python
  x = 3
  nums = [4, 5, 1]
  print(isWinner(x, nums))  # Output: "Ben"
