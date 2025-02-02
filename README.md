# 🗺️ Travel-Guide-AI-Assistant
This project is a real-time AI-powered voice assistant designed to help tourists explore London, UK. It transcribes live speech, generates AI responses using OpenAI's GPT, and provides voice feedback using ElevenLabs.


## 🎯 Features
* Real-time speech-to-text transcription using AssemblyAI

* AI-generated responses powered by OpenAI's GPT-4o

* Text-to-speech voice output using ElevenLabs

* Interactive and conversational travel guide experience


## 🚀 How It Works
1️⃣ The assistant starts by greeting the user with a voice message.

2️⃣ It listens to the user's voice and transcribes it in real-time.

3️⃣ The query is sent to GPT-4o for a smart AI-generated response.

4️⃣ The assistant then speaks the response using ElevenLabs.

5️⃣ The loop continues, making it an interactive conversation! 🗣️


## 🏗️ Tech Stack
* Python 🐍

* OpenAI GPT-4o 🤖

* AssemblyAI (Speech-to-Text) 🎙️

* ElevenLabs (Text-to-Speech) 🔊


## 🛠️ System Dependencies
Before running the script, make sure the following dependencies are installed on your system


🎵 MPV (Required for ElevenLabs Audio Streaming)

This is required for ElevenLabs to stream audio.

* 🖥️ Windows

  1. Download mpv from [here](https://mpv.io/)

  2. Add it to your system PATH.

* 🍏 Mac (macOS)
  ```
  brew install mpv
  ```

* 🐧 Linux (Ubuntu/Debian)
  ```
  sudo apt update && sudo apt install mpv
  ```

🎤 PortAudio & PyAudio (Required for AssemblyAI Transcription)

PortAudio is required to use PyAudio, which AssemblyAI needs for real-time transcription.

* 🖥️ Windows
  ```
  pip install pyaudio
  ```

* 🍏 Mac (macOS)
  ```
  brew install portaudio  
  pip install pyaudio
  ```

* 🐧 Linux (Ubuntu/Debian)
  ```
  sudo apt update && sudo apt install portaudio19-dev  
  pip install pyaudio
  ```
