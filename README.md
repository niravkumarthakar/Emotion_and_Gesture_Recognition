# 🤖 Gesture & Emotion Detection using Deep Learning

This project detects human **gestures** and **facial emotions** in real time using pre-trained deep learning models built with TensorFlow/Keras and OpenCV.

---

## 📌 Project Highlights

* 🔍 **Gesture Detection**:

  * Recognizes hand gestures like: `fist`, `pointing`, `fine`, `ok`, `no`, `victory`
* 🙂 **Emotion Detection**:

  * Detects facial emotions such as: `happy`, `sad`, `angry`, `surprised`, `neutral`, `fear`, `disgust`
* 📆 Trained models saved as `.h5` files
* 💽 Real-time video capture using OpenCV
* 🎯 Simple interface for live prediction

---

## 🧠 Model Details

| Model Type    | File Name          | Framework        | Input Format              |
| ------------- | ------------------ | ---------------- | ------------------------- |
| Gesture Model | `gesture_model.h5` | TensorFlow/Keras | Hand Region (from webcam) |
| Emotion Model | `emotion_model.h5` | TensorFlow/Keras | Grayscale face ROI        |

---

## 🚀 Getting Started

### ✅ Requirements

Install required libraries:

```bash
pip install -r requirements.txt
```

---

### 📂 Project Structure

```
Gesture_Emotion_Project/
├── assets/
│   └── demo.gif
├── models/
│   ├── gesture_model.h5
│   └── emotion_model.h5
├── Gesture_Emotion_Inference.ipynb
├── requirements.txt
├── README.md
```

---

## 💗 How to Run

### 🧪 Run in Jupyter Notebook:

```bash
jupyter notebook Gesture_Emotion_Inference.ipynb
```

### 💻 Run in Python (if script version is available):

```bash
python app.py
```

---

## 💡 Use Cases

* Human-computer interaction
* Virtual assistants
* Sign language interpretation
* Mood-based recommendations

---

## 📚 Dataset Sources

* 👋 **Gestures**: Custom hand gesture dataset 
* 😊 **Emotions**: FER-2013 Dataset or custom labeled facial expressions

---

## 🙌 Acknowledgements

* TensorFlow & Keras
* OpenCV
* Kaggle & Google Colab

---

## 📬 Contact

**Nirav Thakar**
[LinkedIn](https://www.linkedin.com/in/niravkumar-thakar-095132371/) 

---

⭐ *Star this repo if you found it helpful!*
