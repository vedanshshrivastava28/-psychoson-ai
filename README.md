# -psychoson-ai
An advanced AI-powered mental health assistant built using Streamlit, Keras, OpenAI/Gemini API, and computer vision. It detects emotions from images, provides therapeutic chat responses, voice journaling, crisis support, and mood-driven journaling to enhance mental wellness.
# 🧠 pSychoson AI – Mood Tracker with Emotion Detection

**pSychoson AI** is an advanced mental health web app that uses **real-time emotion detection** to guide users through mood journaling, AI therapy chats, and crisis support. Built using **Streamlit**, **TensorFlow/Keras**, **Google Gemini API**, **Whisper**, and more, it provides an emotionally intelligent assistant for mental wellness.

## 🚀 Features

- 🎭 **Real-Time Emotion Detection** via webcam or uploaded image  
- 🔊 **Voice Feedback** using `gTTS` and `pygame`  
- 🧘 **Mood-Driven Journaling** with tailored prompts  
- 🧑‍⚕️ **AI Therapist Chatbot** powered by Gemini  
- 🆘 **Crisis Mode** for "Sad" or "Fear" emotions  
- 🗣️ **Speech Recognition** with Google STT for hands-free input  
- 🎨 **Clean, modern UI** built with Streamlit and HTML/CSS

## 📷 Emotion Classes

The model can detect the following emotions:
- Angry
- Disgust
- Fear
- Happy
- Neutral
- Sad
- Surprise

## 🧰 Technologies Used

| Tool | Purpose |
|------|---------|
| `Streamlit` | Web interface |
| `Keras` | Emotion detection CNN model |
| `OpenCV` | Face detection (Haar Cascade) |
| `gTTS` & `pygame` | Text-to-Speech |
| `speech_recognition` | Voice input |
| `Gemini API (Google)` | AI therapist chatbot |
| `Pillow` | Image handling |
| `NumPy` & `cv2` | Image preprocessing |

## 🗂️ Project Structure

psychoson_ai/
│
├── emotion_model.h5
├── emotion_model.json
├── haarcascade_frontalface_default.xml
├── streamlit_app.py
├── requirements.txt
└── README.md


1. **Clone the repo**
```bash
git clone https://github.com/your-username/psychoson-ai.git
cd psychoson-ai
Create a virtual environment (optional but recommended)
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
pip install -r requirements.txt
streamlit run streamlit_app.py
