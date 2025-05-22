# GenAI
# 🗣️ Speech-to-Text Transcription System

This project demonstrates a functional speech-to-text system using pre-trained models such as **Facebook’s Wav2Vec2** and **OpenAI Whisper**. The system is capable of transcribing short audio clips, including speech embedded in music or noise, with improved accuracy using vocal separation.

---

## 🚀 Features

- 🎧 Transcribes `.wav` audio files to text
- 🤖 Uses powerful pre-trained models (`Wav2Vec2`, `Whisper`)
- 🎛️ Separates vocals from music (using `spleeter`)
- ✅ Compatible with noisy or real-world audio
- 🧹 Optional grammar correction for output

---

## 📁 Project Structure

```bash
📦speech-to-text/
 ┣ 📄 speech_to_text.ipynb        # Main notebook for Wav2Vec2 and Whisper
 ┣ 📄 cleaned_speech_to_text.ipynb # Cleaned version for GitHub
 ┣ 📄 Pop1.wav                     # Sample audio file
 ┣ 📄 requirements.txt            # Python dependencies
 ┗ 📄 README.md                   # This file

🛠️ How to Run
✅ Option 1: Run in Google Colab
Recommended for beginners
Upload your audio file (.wav or .mp3)
Open the notebook speech_to_text.ipynb
Run each cell to:
Mount Drive (if needed)
Load audio
Apply vocal separation
Transcribe using Wav2Vec2 or Whisper

🧪 Technologies Used
Library/Tool	Purpose
transformers	Pre-trained models (Wav2Vec2)
whisper	OpenAI's speech model
spleeter	Vocal/music separation
librosa, torchaudio	Audio preprocessing
language_tool_python	Grammar correction (optional)

📥 Example Transcription
Input Audio: Pop1.wav
Transcription Output:

"This is Peter, this is Johnny, Kenny, and Jora. We just wanted to take a minute to thank you."

🧹 Optional Enhancements
Add GUI with Streamlit or Gradio
Deploy as API (Flask or FastAPI)
Real-time mic transcription (local version)

📌 Notes
Models work best with clear, mono, 16kHz audio.
For mixed audio (music + speech), use spleeter before transcription.
Whisper gives better results than Wav2Vec2 for natural or noisy speech.

🏁 Final Deliverables
✔️ Functional Colab notebook
✔️ Clean .ipynb file for GitHub
✔️ Sample audio
✔️ README with usage guide

📜 License
This project is for educational use under the MIT License.

🙌 Acknowledgements
Facebook AI Research for Wav2Vec2
OpenAI for Whisper
Deezer for Spleeter



