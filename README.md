# 🤖 Dada - Personal AI Voice Assistant

**Dada** is your personalized voice-controlled assistant built with Python. It listens for the wake word **"Dada"**, responds intelligently using AI (via OpenRouter), and can perform various tasks like opening applications, searching Google, playing YouTube videos, and more — all hands-free.

---

## 🎯 Features

- 🎤 Voice input via microphone using `speech_recognition`
- 🗣️ Text-to-speech replies with `pyttsx3`
- 🤖 AI chat responses via **OpenRouter API** (`deepseek-mixtral-8x7b-instruct`)
- 🔍 Google search and web browsing
- ▶️ YouTube video playback using `pywhatkit`
- 💻 Local system commands:
  - Open Chrome
  - Open WhatsApp
  - Open custom folders
  - Shutdown system
- 🧠 Smart command parsing
- 🚪 Wake word activation ("Dada") and exit on "bye", "exit", "stop", or "quit"

---

## 📦 Installation

### ✅ Prerequisites

- Python 3.10+
- Windows OS (Tested on Windows 10/11)
- Working microphone
- Internet connection

### 📥 Install Required Libraries

Open terminal and run:

```bash
pip install speechrecognition pyttsx3 requests pygetwindow pywhatkit pyaudio


