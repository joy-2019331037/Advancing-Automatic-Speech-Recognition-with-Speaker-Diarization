
# 🎙️ Advancing Automatic Speech Recognition with Speaker Diarization

## 📌 Overview
This project focuses on developing an **Automatic Speech Recognition (ASR)** system for transcribing spoken **Bangla** while distinguishing between different speakers. Our objective is to label and annotate **100 hours** of audio data to improve speaker diarization and transcription accuracy.

## 🎧 Data Collection & Annotation
We have collected audio data from various sources, including:
- 🎤 **YouTube talk shows**
- 🗣️ **Debates**
- 🏛️ **Parliamentary sessions**

### 📝 Annotation Process
1. **🔍 Audio Segmentation:** We listen to each audio file and segment the speech by identifying speakers and their respective timestamps.
2. **✍️ Transcription:** Each segment is transcribed manually.
3. **👤 Speaker Labeling:** We annotate the speaker for each segment using **ELAN software**.
4. **📡 Real-life Data:** We are currently collecting real-life recorded audio data to enhance our dataset.

### 📊 Progress So Far
- ✅ **Collected Audio Data:** 41 hours
- ✏️ **Manually Transcribed Data:** 34 hours
- 🔖 **Fully Annotated Data:** 16 hours
- 🎯 **Target:** 100 hours of annotated data

## ⚙️ Methodology
### 🔊 Speaker Diarization
We have utilized **pyannote-segmentation 3.0** for speaker diarization, achieving a **DER (Diarization Error Rate) of 19%**.

### 🗣️ Automatic Speech Recognition (ASR)
We are currently exploring different ASR models to generate accurate Bengali transcriptions:
- 🤖 **Whisper (by OpenAI)**
- 🎙️ **Google ASR**
- 🔍 **Other potential ASR models**

## 🚀 Future Plans
- 🔹 Improve **speaker diarization accuracy** by fine-tuning models.
- 🔹 Enhance **Bengali speech transcription** with state-of-the-art ASR models.
- 🔹 Increase dataset diversity by incorporating **real-life conversational data**.



---

_This repository is a part of an ongoing thesis research._ 📚