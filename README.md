# 🎙️ Advancing Automatic Speech Recognition with Speaker Diarization

## 📌 Overview
This project focuses on developing an **Automatic Speech Recognition (ASR)** system for transcribing spoken **Bangla** while distinguishing between different speakers. Our objective is to label and annotate **100 hours** of audio data to improve speaker diarization and transcription accuracy.

## 🎧 Data Collection & Annotation
We have collected audio data from various sources, including:
-  **YouTube talk shows**
-  **Debates**
-  **Parliamentary sessions**
- **Bangla Podcasts**
- **Quiz Shows**

### 📝 Annotation Process
1. **🔍 Audio Segmentation:** We listen to each audio file and segment the speech by identifying speakers and their respective timestamps.
2. **✍️ Transcription:** Each segment is transcribed manually.
3. **👤 Speaker Labeling:** We annotate the speaker for each segment using **ELAN software**.
4. **📡 Real-life Data:** We are currently collecting real-life recorded audio data to enhance our dataset.

### 📊 Progress So Far
- ✅ **Collected Audio Data:** 81 hours
- 🔖 **Fully Annotated Data:** 70 hours
- 🎯 **Target:** 100 hours of annotated data

## ⚙️ Methodology
### 🔊 Speaker Diarization
We have utilized **pyannote-segmentation 3.0** for speaker diarization, achieving a **DER (Diarization Error Rate) of 10%**.

### 🗣️ Automatic Speech Recognition (ASR)
We are currently exploring different ASR models to generate accurate Bengali transcriptions:
- 🤖 **Whisper (by OpenAI)** — *fine-tuned on our dataset*
- 🔍 **Wav2vec2** 

## 📈 Results
After fine-tuning **Whisper-small** on our dataset, we achieved:
- **Word Error Rate (WER):** ~46%
- **Character Error Rate (CER):** ~21%

### 🔍 Sample Predictions

**Audio Name:** `p5_104.mp3`  
- **Original:**  
> আমি বলি আমাকে স্যার বইলেন আমাকে ভাই বলেন আমার ওই ব্যাপারটা কাজ করে আমাকে স্যার বলার দরকার নাই আমাকে ভাই বলেন তারপর আসলে  
- **Predicted:**  
> বলে আমাকে সার্পোইলেন আমাকে ভাই বলেন আমার ওই ব্যাপারটা কাজ করে আমাকে সার্পোলার দরকান আমাকে ভাই বলেন তারপর আসলে  

---

**Audio Name:** `p2_490.mp3`  
- **Original:**  
> কিন্তু কিছু জিনিস ভাইয়া আছে যেমন আপনি ড্রইং করতে শিখতে চান আপনি আমার কাগজ কলমে ড্রইং শিখে আসলে ব্যবসা নাই টাকা নাই আবার  
- **Predicted:**  
> কিন্তু কিছু জিনিস ভাইয়া আছে যখন আপনি ডোয়াইং করতে শিখতে চাম হুম আপনি কাকজ কোন আমি ডোয়াইং শিখে আসলে ব্যবসা নাই টাকা  

---

## 🚀 Future Plans
- 🔹 Improve **speaker diarization accuracy** by fine-tuning models.
- 🔹 Explore advance models like Wav2vec2 to achieve better accuracy for Bangla **ASR** .
- 🔹 Enhance **Bengali speech transcription** with state-of-the-art ASR models.
- 🔹 Increase dataset diversity by incorporating **real-life conversational data**.

---

_This repository is a part of an ongoing thesis research._ 📚
