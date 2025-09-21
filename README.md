# CodeAlpha Task 2 - Speech Emotion Recognition  

This repository contains my implementation of **Task 2: Emotion Recognition from Speech** for the Code Alpha Internship program.  

## 📌 Objective  
The goal of this project is to recognize human emotions (e.g., happy, sad, angry, fearful, neutral, etc.) from speech audio samples using machine learning and deep learning techniques.  

## 📂 Dataset  
- **Dataset Used:** [Toronto Emotional Speech Set (TESS)]  
- The dataset contains audio recordings of actors speaking in different emotional tones.  
- Emotions covered: *Angry, Disgust, Fear, Happy, Neutral, Pleasant Surprise, Sad*.  

## ⚙️ Approach  
1. **Data Preprocessing**  
   - Loaded audio files using `librosa`.  
   - Extracted features: **MFCCs (Mel-Frequency Cepstral Coefficients)**.  
   - Converted extracted features into a structured CSV file for easier training.  

2. **Model Building**  
   - Implemented an **LSTM (Long Short-Term Memory)** model.  
   - Input: MFCC feature vectors.  
   - Output: Emotion class labels.  

3. **Training & Evaluation**  
   - Trained the model on extracted features from TESS dataset.  
   - Evaluated performance using accuracy and confusion matrix.  

## 🛠️ Tech Stack  
- **Programming Language:** Python  
- **Libraries Used:**  
  - `librosa` → Audio feature extraction  
  - `numpy`, `pandas` → Data handling  
  - `tqdm` → Progress visualization  
  - `scikit-learn` → Preprocessing & evaluation  
  - `tensorflow / keras` → LSTM model building  

## 📊 Results  
- Successfully trained an **LSTM-based model** on multiple emotions.  
- The system can classify speech audio into different emotion categories.  

## 🚀 How to Run  
1. Clone this repository:  
   ```bash
   git clone https://github.com/<your-username>/CodeAlpha-Task2-Speech-Emotion-Recognition.git

📌 Internship Note

This project is completed as part of Code Alpha Internship – Task 2.
It demonstrates the use of Deep Learning (LSTM) for Speech Emotion Recognition.
