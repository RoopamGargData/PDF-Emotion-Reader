# PDF-Emotion-Reader
A Python tool that converts PDF text to voice with emotion detection
# 📘 PDF Emotion Reader — Text-to-Speech with Emotion Detection

This Python tool reads a PDF file and converts its content into speech while detecting the emotional tone of the text (happy, sad, or neutral).

---

## 🔥 Features

- 📄 Extracts text from any PDF
- 🎯 Analyzes emotional sentiment using TextBlob
- 🗣️ Converts text to speech using pyttsx3 with voice tone tuning
- 💡 Accessible reading experience for visually impaired or elderly users

---

## 🧪 How It Works

1. Extracts text from a user-selected PDF
2. Analyzes text sentiment to classify it as:
   - Happy
   - Sad
   - Neutral
3. Reads the text aloud in a matching voice tone

---

## 🛠️ Tech Stack

- `Python`
- `PyPDF2`
- `TextBlob`
- `pyttsx3`

---

## 🚀 How to Run

1. Clone the repository:

```bash
git clone https://github.com/RoopamGarg04/PDF-Emotion-Reader.git
cd PDF-Emotion-Reader

2. Install dependencies:

pip install -r requrements.txt

3. Run the script:

python pdftext_to_audio.py

