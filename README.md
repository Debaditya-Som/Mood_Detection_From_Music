# 🎵 Mood Detection from Music

![Python](https://img.shields.io/badge/Python-3.8+-green.svg)
![ML Project](https://img.shields.io/badge/Machine%20Learning-Music%20Mood%20Classifier-purple)

An AI-powered project that detects the **mood of a listener based on the music they are playing**. This system analyzes audio features from a song to classify the listener’s emotional state as one of the following moods: `Happy`, `Sad`, `Energetic`, or `Calm`.

---

## 🧠 Project Overview

This project uses machine learning to map audio features of music to emotional states. It’s ideal for building smart playlist generators, mood-aware applications, and personalized music recommendations.

---

## 📌 Key Features

- 🎶 Extracts relevant audio features (tempo, energy, valence, etc.)
- 🧠 Uses a trained ML model to predict mood
- 📊 Real-time mood classification (in supported UI)
- 🔌 API-ready architecture for integration
- 🌐 Planned React frontend (optional)

---

## 🛠️ Tech Stack

- **Python** (NumPy, pandas, scikit-learn)
- **Librosa** for audio analysis
- **Matplotlib/Seaborn** for visualization
- **Google Colab** for prototyping
- **ReactJS** frontend

## 🧩 How It Works

1. Extract features from the input audio (e.g., from Spotify or uploaded .mp3):
   - Tempo, Energy, Loudness, Spectral Contrast, etc.
2. Clean and scale the features.
3. Feed them into a trained ML model.
4. Output one of the 4 moods:
   - 😊 Happy
   - 😔 Sad
   - 😌 Calm
   - ⚡ Energetic

