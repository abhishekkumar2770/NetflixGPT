# 🎬 Netflix GPT

A **Netflix Clone** with AI-powered movie search built using **React, Redux, Firebase, TailwindCSS, TMDB API, and OpenAI GPT**.  
Users can sign up, browse trending movies, and get AI-based movie suggestions.

---

## 🚀 Features

### 🔐 Authentication
- Sign Up & Sign In using **Firebase Authentication**
- Redirect between **Login** and **Browse** based on auth state
- Profile Update (Display name & profile picture)
- Sign Out functionality

### 🎥 Browse Page (after login)
- **Header**
- **Main Movie**
  - Autoplay YouTube Trailer (muted)
  - Movie Title & Description
- **Movie Suggestions**
  - Multiple Movie Lists  
  - Beautiful UI with TailwindCSS  

### 🤖 NetflixGPT (AI Movie Search)
- GPT-powered **Movie Search Bar**
- Fetches **movie suggestions** from TMDB based on GPT response
- Multi-language support
- Uses reusable `MovieList` component for results

---

## 🛠️ Tech Stack
- **Frontend**: React, TailwindCSS
- **State Management**: Redux Toolkit
- **Authentication**: Firebase
- **Database & Hosting**: Firebase
- **API**: TMDB API, OpenAI GPT API
- **Deployment**: Firebase Hosting / Vercel

---

## 📂 Project Structure
