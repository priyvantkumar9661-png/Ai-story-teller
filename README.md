# 🧠 AI Story Teller

**AI Story Teller** is a multi-modal storytelling engine that transforms user prompts and uploaded images into vivid, multi-chapter narratives. Powered by Google's Gemini API and Hugging Face's BLIP model, it offers tone and length customization, and exports stories as PDF and MP3 files. A Streamlit web app makes the experience interactive and shareable.

---

## 🚀 Features

- ✍️ **Prompt-Based Story Generation** using Gemini 2.5 Flash
- 🖼️ **Image Captioning** with BLIP (Hugging Face)
- 📚 **Multi-Chapter Story Creation** with tone and length control
- 📄 **PDF Export** using ReportLab
- 🔊 **MP3 Narration** via gTTS (Google Text-to-Speech)
- 🌐 **Streamlit Web App** with optional ngrok tunneling for public access

---

## 🧰 Tech Stack

- Python, Colab Notebook
- Gemini API (`google.generativeai`)
- Hugging Face Transformers (`BLIP`)
- Streamlit, Pyngrok
- ReportLab, gTTS, Pillow

---

## 📦 Installation

```bash
pip install -q transformers pillow google-generativeai timm gtts reportlab streamlit pyngrok

🖼️ Image to Story Workflow
Upload one or more images

Generate captions using BLIP

Convert captions into a story outline

Generate multi-chapter story using Gemini

Export as PDF and MP3

🔐 API Keys
Set your Gemini API key securely:
%env GEMINI_API_KEY=your_key_here
Avoid hardcoding keys in public notebooks. Use .env files or secret managers when deploying.

📄 License
This project is licensed under the MIT License. Feel free to use, modify, and share with attribution.

🙌 Acknowledgments
Google Generative AI team

Hugging Face for BLIP

Streamlit for the interactive UI

ReportLab and gTTS for export features

✨ Author
Priyvant Kumar
Passionate about AI, storytelling, and healthcare innovation. Connect on LinkedIn and explore more projects on GitHub.
