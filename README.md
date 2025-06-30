# Multimodal Transcriber with Gemini Summarisation

Welcome to the **Multimodal Transcriber with Summarisation** project! This application allows you to upload **PDFs, audio files, and videos** for seamless transcription using Google Cloud Speech-to-Text and PDF extraction tools. It also provides **summarisation powered by Google Gemini (via Vertex AI)** to give you a concise overview of your content in British English.

https://medium.com/@roushanakrahmat/building-meetingmind-a-multimodal-meeting-transcription-and-summarisation-assistant-powered-by-152c4741b097

## 🚀 Features
- 📄 **PDF Transcription:** Extract text from PDF files quickly.
- 🎙️ **Audio Transcription:** Supports `.mp3` and `.wav` files with automatic punctuation.
- 🎥 **Video Transcription:** Supports `.mp4` and `.mov` files by extracting audio with FFmpeg.
- ✨ **Summarisation:** Summarises long transcripts using Google's Gemini model on Vertex AI.
- 🎛️ **User-Friendly Interface:** Built with Gradio for an easy drag-and-drop experience.
- 🌍 **Cloud Integration:** Utilises Google Cloud Storage for audio processing.

## 🛠️ Technologies Used
- Google Cloud Speech-to-Text API
- Google Cloud Storage
- Vertex AI (Google Gemini for summarisation)
- Gradio (UI)
- PyMuPDF (fitz)
- FFmpeg
- Python

## 📦 Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/multimodal-transcriber.git
cd multimodal-transcriber
