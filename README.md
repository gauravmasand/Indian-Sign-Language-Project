# Mudra: An AI-Powered Indian Sign Language (ISL) Communication Platform

![SIH 2024 Finalist](https://img.shields.io/badge/Smart%20India%20Hackathon%202024-Top%205%20Finalist-blue.svg)

🏆 **Smart India Hackathon (SIH) 2024 – Top 5 National Finalist** (Software Category, Ministry of Justice)

Mudra is a comprehensive, AI-powered communication platform designed to bridge the gap between the deaf and hearing communities by providing real-time Indian Sign Language (ISL) translation. [cite_start]The system enables seamless, two-way communication between ISL and spoken languages (English/Hindi) across both web and mobile platforms[cite: 42, 89].

[cite_start]This project was developed for the **Smart India Hackathon (SIH) 2024**, where it was selected as a **Top 5 National Finalist** in the software category by the Ministry of Justice[cite: 39, 44, 100].

## Key Features

- [cite_start]**Real-time Two-Way Translation:** Enables conversion between ISL, text, and audio[cite: 43].
- [cite_start]**AI-Powered Gesture Recognition:** Utilizes real-time Machine Learning models built with TensorFlow and MediaPipe for accurate ISL-to-Text conversion[cite: 90].
- **Text-to-ISL Conversion:** Translates written or spoken text into animated ISL gestures.
- [cite_start]**Cross-Platform Accessibility:** A unified experience across a Flutter-based mobile app and a React-based web app[cite: 89].
- [cite_start]**Interactive Learning Modules:** Includes features to help users learn ISL in an engaging way[cite: 89].

## Project Repositories

This project is distributed across multiple repositories, each responsible for a specific component of the system.

| Component | Repository Link | Description |
| :--- | :--- | :--- |
| Backend Server | [gauravmasand/isl-server-sih](https://github.com/gauravmasand/isl-server-sih) | [cite_start]The core Python back-end (FastAPI/Flask) that powers the MLOps pipeline, serving the ML models and managing APIs[cite: 91]. |
| Mobile App | [gauravmasand/SIH-ISL-Mobile-App-Flutter](https://github.com/gauravmasand/SIH-ISL-Mobile-App-Flutter) | [cite_start]The cross-platform mobile application built with Flutter for both Android and iOS[cite: 89]. |
| Web App | [gauravmasand/Indian-Sign-Language-SIH](https://github.com/gauravmasand/Indian-Sign-Language-SIH) | [cite_start]The front-end web application built with React.js, providing browser-based access to the platform[cite: 89]. |
| ML Models | [gauravmasand/SIH-ISL-to-Text-models](https://github.com/gauravmasand/SIH-ISL-to-Text-models) | [cite_start]Contains the custom-trained TensorFlow and MediaPipe models for gesture recognition and translation[cite: 90]. |

---

*This repository serves as a central hub linking to all components of the Mudra project.*
