# 📚 Flipzi – Personal Flashcard Study App

## Description

Flipzi is a mobile flashcard application built with **React Native** and **Expo**, designed to support effective studying through **active recall** and **spaced repetition**.

The app was created as a practical solution to improve long-term retention of computer science concepts, while also serving as a hands-on project to explore real-world mobile development challenges such as state management, persistence, authentication, and API integration.

---

## 📦 Technologies

- React Native
- Expo
- JavaScript
- React Navigation
- AsyncStorage
- Supabase
- OpenAI API
- StyleSheet / Flexbox
- Jest

---

## ✨ Features

### Study & Learning

- Spaced repetition using confidence-based ratings (Easy / Medium / Hard)
- Adaptive review timing based on user performance
- Study session tracking and progress history
- Cards mastered tracking

### Deck Management

- Create, edit, and delete flashcard decks
- Organize flashcards by subject or topic
- Full CRUD support for decks and cards

### AI-Assisted Deck Creation

- Generate flashcards automatically using the OpenAI API
- Create decks from topics or subject descriptions
- Smart question-and-answer generation to speed up study preparation

### User Experience

- Clean, minimalist mobile interface focused on learning
- Touch-optimized interactions
- Subtle haptic feedback for key actions
- Portrait-only layout for consistent study sessions

---

## 🎯 User Interactions

- Tap-based navigation between decks and cards
- Swipe gestures for navigating flashcards
- Button-based confidence rating during study sessions
- Haptic feedback to reinforce user actions

---

## 👩🏽‍🍳 Development Process

- Designed wireframes to define the core study flow and screen layout.
- Implemented navigation and screen structure using React Navigation.
- Built reusable components for decks and flashcards.
- Developed study sessions with spaced repetition logic.
- Added persistent local storage using AsyncStorage.
- Integrated Supabase for authentication and cloud data storage.
- Implemented AI-powered deck generation with the OpenAI API.
- Enhanced the experience with animations, gestures, and haptics.
- Added unit tests to verify core functionality.
- Prepared the app for deployment using Expo tooling.

Each feature was built incrementally and validated before integration into the full study workflow.

---

## 💡 What I Learned

### 🧠 State Management & Study Logic

- Designed confidence-based scheduling logic for spaced repetition.
- Managed complex state across multiple screens and study sessions.

### 📦 Local & Cloud Data Handling

- Implemented persistent local storage with AsyncStorage.
- Synced user data securely using Supabase.
- Handled offline-first scenarios and network issues gracefully.

### 🔐 Authentication & Security

- Implemented secure user authentication with Supabase Auth.
- Managed persistent user sessions.
- Handled sensitive configuration and API keys safely.

### 🤖 API Integration

- Integrated the OpenAI API for automated flashcard generation.
- Managed loading states, errors, and API responses cleanly.

### 📱 Mobile UX & Interaction Design

- Designed touch-first interfaces for mobile devices.
- Applied mobile UX patterns to support focused study sessions.
- Used gestures, animations, and haptic feedback to improve usability.

### 📈 Overall Growth

- Strengthened problem-solving and architectural thinking.
- Gained confidence building production-ready mobile applications.
- Improved ability to balance functionality, usability, and performance.

---

## 💭 Possible Improvements

- Social features for sharing decks
- Advanced study analytics and visualizations
- Improved offline-first synchronization
- Voice-based flashcards for audio learning
- More customization options for study sessions

---

## 🚦 Running the Project

Clone the repository.

Install dependencies:
1. Clone the repository to your local machine.
2. Install the required dependencies: npm install
3. Start the development server: npx expo start
4. Run the app on a device or simulator: npx expo start --ios , npx expo start --android

---

## 🍿 Demo / Video
(Video link to be added) 2025
