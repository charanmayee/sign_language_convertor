# 🖐️ Real-Time Sign Language to Text and Speech Conversion System

## 📌 Overview

This project presents a real-time **Sign Language to Text and Speech Converter** using **Computer Vision** and **Deep Learning**. The system captures hand gestures through a webcam, recognizes them using a trained Convolutional Neural Network (CNN), and converts them into readable text and audible speech.

The goal of this project is to reduce the communication gap between **hearing-impaired individuals** and people who do not understand sign language.

---

## 🎯 Features

* Real-time hand gesture detection using MediaPipe
* Gesture recognition using CNN model
* Conversion of gestures into text
* Text-to-speech output for voice feedback
* User-friendly and low-cost solution

---

## 🛠️ Technologies Used

* **Python**
* **OpenCV** – Image processing and webcam handling
* **MediaPipe** – Hand detection and tracking
* **TensorFlow / Keras** – Deep learning model
* **NumPy** – Numerical operations
* **pyttsx3** – Text-to-speech conversion

---

## 🧠 System Architecture

```
Camera → Hand Detection → Preprocessing → CNN Model → Prediction → Text Output → Speech Output
```

---

## 📂 Project Structure

```
SignLanguageProject/
│
├── dataset/              
│   ├── A/
│   ├── B/
│   └── ...
│
├── templates/            ← ADD THIS
│   └── index.html
│
├── static/               ← ADD THIS
│   └── style.css
│
├── train.py              
├── app.py                
├── hand_detection.py     
├── sign_model.h5         
├── requirements.txt      
└── README.md             

---

## 📊 Dataset

The dataset consists of hand gesture images representing sign language alphabets.

* Images are collected manually or from public datasets
* Each class corresponds to an alphabet (A–Z)
* Data is preprocessed (resizing, normalization) before training

---

## ⚙️ Installation

### 1️⃣ Clone the repository

```
git clone https://github.com/your-username/sign-language-project.git
cd sign-language-project
```

### 2️⃣ Create virtual environment

```
python -m venv venv
venv\Scripts\activate
```

### 3️⃣ Install dependencies

```
pip install -r requirements.txt
```

---

## ▶️ Usage

### Step 1: Train the model

```
python train.py
```

### Step 2: Run real-time detection

```
python app.py
```

### Controls:

* Press **S** → Convert text to speech
* Press **C** → Clear text
* Press **ESC** → Exit

---

## 📈 Expected Results

* Real-time gesture recognition
* Accuracy around **90–95%** (depending on dataset quality)
* Smooth text and speech output

---

## 🚀 Future Enhancements

* Sentence and word-level recognition
* Support for dynamic gestures using LSTM
* Mobile or web application deployment
* Multi-language sign support (ISL, ASL)
* Improved accuracy with larger datasets

---

## 🤝 Applications

* Communication aid for deaf and mute individuals
* Educational tools
* Assistive technology in healthcare and public services

---

## 📌 Conclusion

This project demonstrates how **Artificial Intelligence and Computer Vision** can be used to build socially impactful solutions. It provides a practical and scalable approach to bridging communication gaps using modern technology.

---

## 👩‍💻 Author

**Your Name**
B.Tech Student

---

## ⭐ Acknowledgements

* MediaPipe by Google
* TensorFlow Team
* Open-source datasets and community support

---
