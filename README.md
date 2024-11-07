# Quizinator

Quizinator is a JavaScript-based quiz game that challenges your knowledge of HTML, CSS, and JavaScript through a timed, multiple-choice format. With a responsive timer and instant scoring, this game provides a fun way to test your web development skills!

---

## Table of Contents
- [How to Play](#how-to-play)
- [Features](#features)
- [Game Rules](#game-rules)
- [Code Overview](#code-overview)
- [Customizing Questions](#customizing-questions)
- [License](#license)

---

## How to Play

1. **Start the Game**: The game begins automatically upon loading the page.
2. **Answer Questions**: Each question has four options. Select the correct option to earn points.
3. **Score and Timer**: Monitor the score and remaining time. The game ends when all questions are answered or time runs out.
4. **End and Reset**: After the game, view your score and reset to play again.

---

## Features

- **Timed Quiz**: You have 30 seconds to answer as many questions as possible.
- **Multiple-Choice Questions**: Each question has four options, only one of which is correct.
- **Real-Time Score Display**: Shows your current score.
- **Responsive Timer Bar**: The timer bar visually represents the remaining time.
- **Game Over Screen**: Displays your final score and allows for a reset.

---

## Game Rules

1. **Answer Correctly**: Each correct answer awards 1 point.
2. **Time Limit**: Answer as many questions as possible within 30 seconds.
3. **Game Over**: The game ends when either all questions are answered or the timer reaches zero.

---

## Code Overview

The game is developed using HTML and JavaScript with DOM manipulation to control gameplay and UI elements.

### Key Functions

- **`startGame()`**: Initializes the game, sets up the score and timer, and displays the first question.
- **`showQuestion()`**: Displays the current question and options.
- **`checkAnswer(selectedOption)`**: Validates the selected answer, updates the score if correct, and moves to the next question.
- **`updateTimer()`**: Updates the timer bar and decrements time; ends the game if the time reaches zero.
- **`endGame()`**: Stops the timer and displays the final score.
- **`resetGame()`**: Resets the game to its initial state, allowing a fresh start.

---

## Customizing Questions

The questions array is defined in the JavaScript code. You can add or edit questions to suit your preferences by following this format:

```javascript
const questions = [
    { question: "What does HTML stand for?", options: ["Hyper Text Markup Language", "Home Tool Markup Language", "Hyperlinks and Text Markup Language", "Hyper Transfer Markup Language"], answer: 0 },
    // Add more questions here
];
