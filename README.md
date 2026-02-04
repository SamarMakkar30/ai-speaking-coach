# ai-speaking-coach
An AI-powered voice assistant designed to help users improve English speaking skills through real-time conversation practice, speech recognition, and AI-generated feedback.

This project focuses on integrating speech processing, generative AI, and an interactive UI into a seamless learning experience.

🎯 Project Objective

To create a conversational system that enables users to:

Practice spoken English in real-time

Receive AI-generated conversational responses

Get immediate spoken feedback

Improve fluency and confidence

🏗 System Overview
User Speech
   ↓
Speech-to-Text (SpeechRecognition)
   ↓
AI Response Generation (Gemini API)
   ↓
Text-to-Speech (pyttsx3)
   ↓
Spoken Feedback to User

✨ Key Features

🎙 Voice-based user interaction

🤖 AI-powered conversation simulation

🔊 Text-to-speech feedback

🖥 Interactive Streamlit web interface

⚡ Real-time speech processing

🤖 AI Integration

Uses Google Gemini API for context-aware conversational responses

Generates natural dialogue for speaking practice

Maintains conversational flow during user interaction

🔊 Speech Processing
Component	Purpose
SpeechRecognition	Converts user voice input into text
pyttsx3	Converts AI text responses into spoken output
📁 Project Structure
ai-speaking-coach/
├── app.py              # Streamlit application
├── speech_utils.py     # Speech recognition & TTS logic
├── ai_response.py      # Gemini API interaction
├── requirements.txt
└── README.md

🚀 Running the Project
Install dependencies
pip install -r requirements.txt

Run application
streamlit run app.py

🛠 Tech Stack

Python, Streamlit, SpeechRecognition, pyttsx3, Google Gemini API, Generative AI

⚠️ Note

This project is intended for language learning support and demonstration of speech-AI integration. It is not a certified language assessment system.
