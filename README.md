# Virtual Assistant with Python NLP (Initial Phase)

This repository documents the initial phase of a Virtual Assistant project, focusing on the implementation of the **Text-to-Speech (TTS)** core functionality.

The project is configured to run on **Google Colab**, which ensures easy dependency installation and execution across different environments.

## Implemented Functionality: Text-to-Speech (TTS)

This first phase is dedicated to the assistant's **Voice Output**. The TTS functionality allows the assistant to convert any provided text into audible speech in real time.

### Key Features

* **Colab Playback:** The code is specifically adapted to play back the audio directly within the Google Colab notebook environment.
* **Automatic Cleanup:** The system ensures that temporary audio files are deleted after playback, maintaining a clean execution environment.

---

## Technologies and Libraries Used

| Technology | Primary Function | Project Details |
| :--- | :--- | :--- |
| **Google Colaboratory** | Development Environment | Used as the main platform for running the Python code (cloud-hosted Jupyter Notebook). |
| **Python** | Programming Language | The base language for the TTS functionality. |
| **`gTTS` (Google TTS)** | Text-to-Speech Conversion | Primary library used to generate the audio from text (configured for Portuguese: `lang='pt'`). |
| **`IPython.display.Audio`** | Audio Playback | Essential module used to render and play the resulting MP3 audio within the Colab console. |
| **`os` and `time`** | Utilities | Used for file management and controlling the playback duration/wait time. |
