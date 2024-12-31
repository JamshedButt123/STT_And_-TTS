# 🗣️ **Text-to-Speech and Audio Transcription Demo**  

This repository contains two scripts demonstrating **Text-to-Speech (TTS)** and **Audio Transcription** functionalities using 🐸 **TTS library** and **OpenAI's Whisper model**.  

## 📂 **Files Overview**  

1. **`TTS_Demo.py`**  
   - A Python script utilizing the 🐸 **TTS library** for text-to-speech conversion.  
   - Supports multilingual voice cloning.  
   - Allows saving the generated speech to an audio file (`output.wav`).  

2. **`whisper_Audio_small.ipynb`**  
   - A Jupyter Notebook demonstrating **audio transcription** using OpenAI's **Whisper model**.  
   - Transcribes audio files into text efficiently.  

## ⚙️ **Setup and Installation**  

### Prerequisites  
- **Operating System:** Ubuntu 18.04 or later (recommended)  
- **Python Version:** Python ≥ 3.9  

### Install Required Libraries  
Run the following command to install 🐸TTS and other dependencies:  

```bash
pip install TTS torch openai-whisper
```  

Ensure your Python environment meets the specified version and OS requirements.  

## 🚀 **Usage**  

### **1. Text-to-Speech (`TTS_Demo.py`)**  
Run the script to generate speech from text:  

```bash
python TTS_Demo.py
```  

- The output audio file will be saved as `output.wav`.  
- You can modify the `speaker` variable in the script to change the voice.  

### **2. Audio Transcription (`whisper_Audio_small.ipynb`)**  
Open the Jupyter Notebook:  

```bash
jupyter notebook whisper_Audio_small.ipynb
```  

- Follow the notebook's instructions to transcribe audio files.  
- Ensure the required Whisper model is downloaded locally.  

## 📊 **Customization**  

- **Speaker Selection:** Update the `speaker` variable in `TTS_Demo.py` to use a different voice.  
- **Text Input:** Modify the text string to generate different speech output.  
- **Audio Input:** Update the audio path in the Jupyter Notebook for transcription.  

## 🛠️ **Troubleshooting**  

- Ensure Python dependencies are installed correctly.  
- Verify models are downloaded and accessible locally.  
