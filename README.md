# voice-_assistent

Chatbot – Gemini 2.0 Flash with Voice Support (Google Colab)
An interactive AI chatbot powered by Google Gemini 2.0 Flash, featuring optional voice input via your browser’s microphone — fully compatible with Google Colab.

✨ Speak naturally or type your questions — Gemini listens and responds in real time! 

🌟 Features
✅ Text-based chat (traditional input)
🎙️ Voice input support using browser microphone (no pyaudio needed)
💬 Streaming responses from Gemini (shows text as it's generated)
🔁 Persistent chat history within session
🧪 Built for Google Colab — works around Colab’s microphone limitations
🚀 Uses the fast and efficient gemini-2.0-flash model
🚀 Quick Start (Google Colab)
Open in Colab:
Open In Colab
Copy the full code from chatbot_colab.py (or the single-cell version below) into a Colab notebook cell.
Replace the API key:
python


1
GEMINI_API_KEY = "enter_your_own_API_key"
→ Get your key from Google AI Studio
Run the cell and follow prompts:
Type text to chat via keyboard
Type voice to speak (allow mic access in browser)
Type quit to exit
🔧 Requirements
Python 3.8+
Google account (for Colab)
Internet connection (required for speech recognition & Gemini API)
Automatically Installed in Colab:
txt


1
2
google-generativeai
SpeechRecognition
❗ No local setup needed — runs entirely in your browser via Colab! 

⚠️ Limitations
Voice input only works in live Colab sessions (not in exported scripts).
Audio recording limited to 10 seconds per turn (configurable in JS).
Speech recognition uses Google Web Speech API (requires internet, English-optimized by default).
No microphone access in Colab if running in restricted environments (e.g., some corporate networks).
💡 Tips
For best voice results: speak clearly in a quiet room.
First run may take 10–15 seconds (installs dependencies).
You can extend this to support text-to-speech replies using gTTS + IPython.display.Audio.
📜 License
This project is open-source and free to use.
Powered by Google Gemini API — subject to Google AI Terms .

🙌 Author
Made with ❤️ by AB
(Customize this as needed!)
