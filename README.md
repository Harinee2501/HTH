# @Lang - AI-Powered Localization Tool


@Lang is an AI-driven localization solution that transforms global video content by providing culturally adapted subtitles, voiceovers, and interactive learning features. Our tool goes beyond literal translation to deliver emotionally intelligent, context-aware localization that resonates with local audiences.

## 🌟 Key Features

### 🎬 Advanced Subtitling
- **Dual-Mode Subtitles**: Choose between smooth context-aware translations or literal word-by-word mapping
- **Emotion-Adaptive Subtitles**: Color cues reflect detected emotions in speaker's voice and expressions
- **Interactive Word Popups**: Click/tap any word for definitions, pronunciation, and usage examples

### 🌍 Cultural Adaptation
- Automatic replacement of idioms, references, and units (e.g., "football" → "soccer" for US audiences)
- Context-aware translation that preserves meaning rather than literal words
- Regional measurement conversions (miles ↔ kilometers, Fahrenheit ↔ Celsius)

### 🔊 Intelligent Voiceovers
- AI-generated speech with authentic regional accents
- Lip-sync technology for natural viewing experience
- Multi-language support with Google Voice integration

### 🎓 Learning Features
- Adaptive subtitle pacing based on viewer behavior
- Progressive difficulty (simple → natural translations as skills grow)
- Helpful hints and examples when viewers pause or rewind

## 🛠 Technical Stack

### Frontend
- **Core**: React 18, JavaScript (JSX), Vite
- **Styling**: CSS3, Inline Styles, Responsive Design
- **Video**: HTML5 Video, Custom Video Player (TrackedVideoPlayer), Multi-format Support
- **State**: React Hooks (useState, useEffect), Local State, Props & Context

### Backend
- **Framework**: Python Flask, Flask-CORS, Werkzeug
- **Video Processing**: FFmpeg, Audio Extraction, Multi-format Support
- **AI**: AssemblyAI API, Universal Speech Model, Real-time Processing
- **APIs**: RESTful, JSON, HTTP Methods
- **Security**: CORS, File Validation, Error Handling

## 🚀 Getting Started

### Prerequisites
- Node.js (v16+)
- Python (v3.8+)
- FFmpeg

### Installation
1. Clone the repository:
```bash
git clone https://github.com/your-repo/lang.git
cd lang
# Project Setup Guide

## Prerequisites
- Node.js (for frontend)
- Python (for backend)
- npm (comes with Node.js)
- pip (Python package manager)

## Frontend Setup
```bash
cd frontend
npm install
Install backend dependencies:

## Backend Setup
```bash
cd ../backend
pip install -r requirements.txt
Set up environment variables (create .env files in both frontend and backend directories)

### Running the Application
Start the backend:

bash
cd backend
python app.py
Start the frontend (in another terminal):

bash
cd frontend
npm run dev

## Access the application at http://localhost:3000
