# 🚀 Face Recognition System using Machine Learning

A **real-time Face Recognition System** built using Python and computer vision techniques. The system detects and recognizes human faces via a webcam using classical machine learning algorithms.

---

## 📌 Project Overview

The system is designed in two key stages:

### 🔹 1. Data Collection

* Captures multiple face samples using a webcam
* Stores data in structured `.npy` format for training

### 🔹 2. Face Recognition

* Trains a model on collected data
* Performs real-time face recognition with identity prediction

---

## 💡 Key Features

* 🔍 Face Detection using **Haar Cascade Classifier**
* 🧠 Face Recognition using **LBPH (Local Binary Patterns Histogram)**
* 🎥 Real-time webcam-based detection and recognition
* 📂 Custom dataset creation and storage
* 👥 Supports multiple users

---

## 🛠️ Tech Stack

* **Language:** Python
* **Libraries:** OpenCV, NumPy
* **Concepts:** Machine Learning, Computer Vision

---

## ⚙️ Installation

Install required dependencies:

```bash
pip install opencv-contrib-python numpy
```

---

## ▶️ How to Run

### Step 1: Data Collection

* Open `collect_faces.ipynb`
* Enter your name when prompted
* System captures and stores face samples

### Step 2: Face Recognition

* Open `recognize_faces.ipynb`
* Model is trained on collected data
* Webcam starts for real-time recognition

---

## 📊 Working

* Uses **Haar Cascade** to detect faces in each frame
* Extracted face data is stored and labeled
* **LBPH algorithm** is used to train the recognition model
* During execution, the model predicts identity along with a confidence score

---

## 📈 Applications

* 🔐 Security & Surveillance Systems
* 🏫 Automated Attendance Systems
* 📱 Smart Authentication Solutions

---

## 🤝 Contribution & Role

This project was developed collaboratively as part of a team.
I contributed to:

* Designing the **end-to-end face recognition pipeline**
* Implementing **data collection and preprocessing**
* Developing the **real-time recognition system**

---

## ⚠️ Limitations

* Performance depends on lighting conditions
* Works best with smaller datasets
* Accuracy may decrease with large-scale data

---

## 🚀 Future Improvements

* Integrate deep learning models (**FaceNet, CNNs**)
* Improve scalability and accuracy
* Develop a GUI-based interface
* Deploy as a web or mobile application

---

---
## 📸 Demo


