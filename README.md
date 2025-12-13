# TextToSignConverter
# 🗣️ SignBridge: Voice-to-Sign Language Translator

> **Breaking silence with code: A comprehensive tool bridging the gap between hearing and speech-impaired communities.**

![Python](https://img.shields.io/badge/Python-3.10-blue?style=for-the-badge&logo=python&logoColor=white)
![Accessibility](https://img.shields.io/badge/Accessibility-ISL%20%26%20ASL-orange?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Active-success?style=for-the-badge)

## 🌟 Overview

**SignBridge** is an assistive technology application designed to facilitate communication for the Deaf and Hard of Hearing (DHH) community.

Most sign language tools focus on one region, but **SignBridge** is built with versatility in mind. It accepts **Voice or Text input** and instantly translates it into accurate sign language animations. Uniquely, it offers dual-support for both **Indian Sign Language (ISL)** and **American Sign Language (ASL)**, making it a powerful cross-cultural communication tool.

## ✨ Key Features

* **🎤 Real-Time Speech Recognition:** Uses advanced speech processing to listen to user input ("You Said: Hello") and convert it to text instantly.
* **🌍 Dual Language Support:**
    * **ISL (Indian Sign Language):** Tailored for the Indian demographic.
    * **ASL (American Sign Language):** Supports international standards.
* **🖼️ Dynamic Visuals:** Fetches and displays the corresponding sign language GIFs or images for every word/letter spoken.
* **🧠 Intelligent GUI:** A clean "Hearing Impairment Assistant" interface that allows users to toggle between languages easily.

## 🛠️ Tech Stack

* **Core Logic:** Python 3.10
* **GUI Framework:** Tkinter / Custom Interface
* **Audio Processing:** `SpeechRecognition`, `PyAudio`
* **Data Handling:** JSON (for mapping phrases to GIF paths)

## 📂 Project Structure

The repository is organized for modularity. To run the app, you must work within the `src` directory.

```text
SignBridge-main/
├── resources/                 # Database of assets
│   ├── asl_gifs/              # Animations for ASL
│   ├── isl_gifs/              # Animations for ISL
│   ├── supported_asl_phrases.json
│   └── supported_isl_phrases.json
├── src/                       # Source Code
│   ├── interface/             # GUI Modules
│   ├── processor/             # Speech Processing Logic
│   └── main.py                # 🚀 ENTRY POINT
└── requirements.txt           # Dependencies
```
📸 Usage & Screenshots
1. Language Selection Dashboard
Upon launching, the user is presented with a choice between ISL and ASL.

<img width="1920" height="1080" alt="Screenshot (165)" src="https://github.com/user-attachments/assets/76726594-769e-44cf-b832-bb532b02805e" />


2. Live Translation
The system listens to the microphone, calibrates background noise, and translates the spoken phrase (e.g., "Hello") into the corresponding video gesture.

<img width="1920" height="1080" alt="Screenshot (166)" src="https://github.com/user-attachments/assets/5bbc370e-2230-4d23-b042-f57cdf25718e" />


🚀 Execution Instructions
Follow these steps exactly to ensure the assets load correctly.

1. Install Dependencies
Navigate to the main folder and install the required Python libraries:
```
pip install -r requirements.txt
```
2. Navigate to Source
Crucial Step: You must change your directory to the src folder before running the script, otherwise the code may not find the resources folder.
```
cd SignBridge-main/src
```
3. Run the Application
```
python main.py
```
Thank You for visiting!!

Developed By Shankari N.

















