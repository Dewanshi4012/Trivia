# Trivia App 🧠
A fun and engaging Android trivia app that challenges your knowledge with interesting questions. Track your scores, test your memory, and improve with every attempt!

## 📖 Introduction
The Trivia App is a dynamic quiz game built for Android devices. It fetches trivia questions from an online API, allowing users to interact with a constantly updated question bank. Users can answer true or false questions, track their current scores, and aim to beat their highest scores—all in an interactive and visually appealing UI.

## ✨ Features
- **Dynamic Question Fetching:** Questions are loaded in real-time from an online API.
- **True/False Quiz Format:** Simple and engaging format for all ages.
- **Score Tracking:** Keeps track of the current score and displays the highest score.
- **Animations for Feedback:** Visual cues (shake for incorrect, fade for correct) make it interactive.
- **Offline State Persistence:** Saves your progress and highest score using shared preferences.

## 🛠️ Tech Stack
- **Programming Language:** Java
- **Android Architecture:**
  - Data Binding
  - Shared Preferences
  - Volley for Networking
- **UI Components:**
  - ConstraintLayout
  - CardView
  - Animations (Shake, Fade)
- **External Libraries:**
  - Volley for API calls

## 🌐 API
The app fetches questions from the following API:
Trivia Questions API: 
 ```bash
  https://raw.githubusercontent.com/curiousily/simple-quiz/master/script/statements-data.json
  ```
## 🚀 How to Use
- **Launch the App:** Start the trivia app to load the first question.
- **Answer Questions:** Tap True or False to answer the current question.
- **Navigate:** Use the Next button to skip to the next question.
- **Score Tracking:** Your score updates in real-time as you play.
- **Beat Your High Score:** Strive to improve and save your highest score.

## 💡 Future Enhancements
- Add more categories of questions.
- Implement a leaderboard to compare scores globally.
- Introduce a timer for added difficulty.
