# MathGame Android Project

A simple and engaging Math Quiz application built with Kotlin for Android. This project challenges users to solve mathematical problems within a time limit, featuring a life-based scoring system.

## 🚀 Features

- **Interactive Operations**: Users can choose between Addition, Subtraction, and Multiplication (Addition is the primary implemented mode).
- **Dynamic Question Generation**: Randomly generates math problems using numbers between 0 and 100.
- **Timed Challenges**: A 60-second countdown timer for each question to increase difficulty and engagement.
- **Scoring & Life System**:
  - **Score**: Earn +10 points for every correct answer.
  - **Lives**: Start with 3 lives. Lose a life for every incorrect answer or when the timer reaches zero.
- **Game Over & Results**: Displays the final score and provides options to play again or exit the application.

## 🛠️ Technology Stack

- **Languge**: Kotlin
- **Framework**: Android SDK
- **UI Design**: XML Layouts with AppCompat
- **Build System**: Gradle (Kotlin Script)

## 📁 Project Structure

- `MainActivity`: The entry point with selection for math operations.
- `GameActivity`: The core gameplay logic handles timers, scoring, and user input validation.
- `ResultActivity`: Displays the final score and allows navigation back to the main menu.

## 📝 Important Information

- **Package Name**: `com.example.mathgame`
- **Main Class**: `MainActivity`
- **Minimum Requirements**: Designed for modern Android devices with Edge-to-Edge support.

---
*Created as part of the CS 218 - Mobile Development for Android course.*
