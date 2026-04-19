---
layout: default
title: Projects
permalink: /projects/
---

## Research Projects

### 🚍🤖 Autonomous Bus Chatbot [Year 2018–2020]

- **Work:** NUS Singapore
- **Description:** Developed a spoken-dialogue system for an autonomous bus to assist passengers with navigation, route guidance, and emergency support.
- 🔊 Integrated advanced ASR and chatbot interfaces for hands-free passenger communication, enabling voice-based queries and support.

#### Tools Involved

- TensorFlow for wakeup-word CNN model development.
- Python Flask for backend server development.
- RASA framework for dialogue management system.
- Docker for environment setup and deployment.

#### Dialogue Management System

- Development of natural language understanding (NLU) module for intent recognition and entity extraction from ASR-generated text.
- Implement dialogue management system to handle multi-turn conversations and context tracking.
- Use Google search as a fallback mechanism to handle out-of-scope queries.

#### Backend Server and Android Client

- Used the Singaporean-accent ASR model trained by the NUS team for localized speech recognition.
- Designed and implemented RESTful APIs for seamless communication between the Android client and backend server.
- Developed a Python Flask server to handle real-time spoken-dialogue interactions and manage passenger queries.

#### Wakeup-word in Android UI

- Implemented a wakeup-word feature to replace traditional push-to-talk interaction, enabling hands-free activation within the Android application.
- Integrated a Convolutional Neural Network (CNN) model using TensorFlow Lite directly in the Android source code for efficient on-device inference.
- Developed and open-sourced the complete implementation, available at: [Hellobus_tflite GitHub repository][hellobusTfliteRepo], including model training scripts and Android integration.
- Provided a Dockerfile for streamlined environment setup and reproducible builds, facilitating easy deployment and testing.

[hellobusTfliteRepo]: https://github.com/maulikmadhavi
