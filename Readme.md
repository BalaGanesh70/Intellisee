# VisionVoice 
A real-time AI-powered system that integrates computer vision and natural language processing to recognize objects via webcam and execute voice-based commands.

---

## Project Overview

**VisionVoice** is a multimodal AI project that combines:
- Real-time object detection using computer vision (CV)
- Voice recognition using speech-to-text (STT)
- Natural Language Processing (NLP) for interpreting user commands
- Decision logic to perform context-aware actions

The system captures a webcam frame, detects objects, listens to the user's command, matches it with detected items, and prints the resulting action.

---

##  Features

-  Real-time object detection via HuggingFace DETR or YOLO models
-  Voice command recognition using Google Speech Recognition
-  NLP-based token matching with detected objects
-  Command-action pairing like “Pick up the bottle”
-  Simple OpenCV interface with keyboard interaction

---

## 🛠️ Tech Stack

| Category        | Tools/Tech Used                              |
|----------------|----------------------------------------------|
| Programming     | Python 3                                     |
| Computer Vision | OpenCV, HuggingFace Transformers (DETR)      |
| NLP             | NLTK / Regex-based tokenizer                 |
| Speech          | SpeechRecognition, PyAudio                   |
| Visualization   | Webcam via OpenCV                            |

---

##  Project Structure


---

##  Installation

1. Clone the repository:
```bash
git clone https://github.com/your-username/visionvoice.git
cd visionvoice

pip install -r requirements.txt

import nltk
nltk.download('punkt')

Run the script:
        python main.py  


Controls:

Press c → Capture frame and speak a command

Press q → Quit the app

Example:

Webcam shows a “cup”

You say: “Pick up the cup”

Output: "Action: cup recognized and matched with command!"

Example Use Cases
Voice-controlled robotics

Smart surveillance assistants

Voice-accessible automation for assistive technology