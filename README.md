# 🗣️ **Text-to-Speech and Audio Transcription Demo**  

This repository contains three scripts demonstrating **Text-to-Speech (TTS)** and **Audio Transcription** functionalities using 🐸 **TTS library**, **OpenAI's Whisper model**, and **GROQ acceleration**.  

## 📂 **Files Overview**  

1. **`TTS_Demo.py`**  
   - A Python script utilizing the 🐸 **TTS library** for text-to-speech conversion.  
   - Supports multilingual voice cloning.  
   - Allows saving the generated speech to an audio file (`output.wav`).  

2. **`whisper_Audio_small.ipynb`**  
   - A Jupyter Notebook demonstrating **audio transcription** using OpenAI's **Whisper model**.  
   - Transcribes audio files into text efficiently.  

3. **`Whisper_large_v3_turbo_using_Groq.ipynb`**  
   - A Jupyter Notebook showcasing **audio transcription with GROQ acceleration**.  
   - Includes multilingual transcription examples in **English** and **Spanish**.  
   - Optimized for real-time processing.  

## ⚙️ **Setup and Installation**  

### Prerequisites  
- **Python Version:** Python ≥ 3.9  

### Install Required Libraries  
Run the following command to install 🐸TTS, Whisper, and GROQ dependencies:  

```bash
pip install TTS torch openai-whisper groq
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

### **3. Audio Transcription with GROQ (`Whisper_large_v3_turbo_using_Groq.ipynb`)**  
Launch the notebook:  

```bash
jupyter notebook Whisper_large_v3_turbo_using_Groq.ipynb
```  

- Follow the provided instructions for transcription using **GROQ acceleration**.  
- Supports multilingual audio files (e.g., English, Spanish).  

## 📊 **Customization**  

- **Speaker Selection:** Update the `speaker` variable in `TTS_Demo.py` to use a different voice.  
- **Text Input:** Modify the text string to generate different speech output.  
- **Audio Input:** Update the audio path in the Jupyter Notebooks for transcription.  

## 🛠️ **Troubleshooting**  

- Ensure Python dependencies are installed correctly.  
- Verify models are downloaded and accessible locally.
## 📈 **Performance Metrics**

Below is the Word Error Rate (WER) and Character Error Rate (CER) of the Whisper large model on Common Voice 15 and FLEURS datasets:
![Whisper image](https://github.com/JamshedButt123/STT_And_TTS/blob/main/n-openai-whisper-new-model-large.png)  
