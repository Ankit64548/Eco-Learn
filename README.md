# EcoLearn Prototype — SIH 2025

A gamified environmental education web app prototype built with HTML/CSS/JS + Firebase (Auth, Firestore, Storage). Map uses Leaflet.

## Features
- Signup/Login (Firebase Auth)
- Interactive Punjab map (district info)
- AI chatbot (prototype rule-based + hook for cloud AI)
- Quizzes with scoring and eco-points
- Leaderboard (top users by eco-points)
- QnA forum (Firestore)
- Real-world task proof submission (photo upload to Firebase Storage)
- Firestore security rules (starter)

## Setup
1. Create a Firebase project and enable Authentication (Email/Password), Firestore and Storage.
2. Replace `firebase.js` config with your project keys.
3. Serve the files via a static server:
   - `python -m http.server 8000` (in project folder) or `npx http-server`
4. Open `index.html` in browser and create accounts.

## Next steps
- Deploy Cloud Function to securely call OpenAI / Dialogflow for a real AI chatbot.
- Add drag-&-drop educational games (waste segregation, water-cycle sim).
- Improve UI/UX and responsiveness.
- Add teacher/admin dashboards and analytics.

# Eco-Learn
