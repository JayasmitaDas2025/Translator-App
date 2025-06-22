# 🌐 AI-Powered Language Translator App

This project is an **AI-powered desktop application** that enables users to translate text across multiple languages with ease. Built using Python and a combination of powerful libraries such as `googletrans`, `gTTS`, `SpeechRecognition`, and `Tkinter`, the app provides an intuitive GUI and integrates text, speech, and audio functionalities for a seamless translation experience.

## 🚀 Features

- 🌍 **Multilingual Translation** using Google Translate API
- 🗣️ **Speech-to-Text Input** via microphone (using SpeechRecognition)
- 🔊 **Text-to-Speech Output** (powered by gTTS and playsound)
- 🖥️ **User-Friendly Interface** built with `Tkinter`
- 💬 **Real-Time Language Detection and Conversion**
- 📥 Accepts manual or audio input and provides translation both as text and spoken output

## 🧰 Tech Stack

- **Frontend/UI**: Tkinter (Python GUI library)
- **Translation Engine**: `googletrans` (Google Translate unofficial API)
- **Text-to-Speech**: `gTTS` (Google Text-to-Speech)
- **Speech Recognition**: `SpeechRecognition` + `PyAudio`
- **Backend**: Python (modular script logic)

## 🛠️ Installation

Make sure you have Python 3 installed. Then, install the necessary dependencies:

```bash
pip install git+https://github.com/BoseCorp/googletrans.git
pip install googletrans==3.1.0a0
pip install gTTS playsound
pip install SpeechRecognition pyaudio
pip install tk
pip install flask
```

## 📸 Screenshots

*(Include screenshots of your UI in this section for better presentation)*

## 📁 Project Structure

```
.
├── app.py              # Main application script with GUI
├── translator_icon.ico # App icon (optional)
├── README.md           # Project documentation
└── requirements.txt    # All dependencies
```

## ✅ Usage

1. Run the app:
   ```bash
   python app.py
   ```

2. Enter the text, choose the target language, and get the translated result instantly.
3. Use the microphone input option for voice translation.
4. Listen to the translated output via speaker.

## 🔤 Supported Languages

Supports all languages available in Google Translate (see [Googletrans LANGUAGES](https://py-googletrans.readthedocs.io/en/latest/#googletrans-languages)).

## 📌 Note

Ensure microphone access and speaker output are enabled on your system for full functionality.
