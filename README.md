# 🎥 Violence Detection System with Deep Learning

> Detect violent activity in short videos using a deep learning model powered by CNN+LSTM and an intuitive Gradio interface.

---

![GitHub stars](https://img.shields.io/github/stars/AdeelAliYousaf/ViolenceDetectionSystem?style=social)
![GitHub forks](https://img.shields.io/github/forks/AdeelAliYousaf/ViolenceDetectionSystem?style=social)
![GitHub license](https://img.shields.io/github/license/AdeelAliYousaf/ViolenceDetectionSystem)
![TensorFlow](https://img.shields.io/badge/TensorFlow-2.x-orange)
![Python](https://img.shields.io/badge/Python-3.7%2B-blue)

---

## 🚀 Overview

This project leverages a **Convolutional Neural Network + LSTM** model to analyze video frames and detect **violent behavior**. It is designed to work with short video clips and offers an easy-to-use **Gradio web UI**.

---

## 📦 Features

- 🎯 Pre-trained `.keras` model (CNN + LSTM architecture)
- 🎥 Processes 30 RGB frames per video (160×160)
- ⚡ Fast and efficient predictions
- 🖥️ Gradio frontend to upload and test any short video
- 🌐 Deployable locally or online

---

## 🔍 Model Architecture

- **Base**: Convolutional layers for spatial feature extraction
- **Temporal**: LSTM layer to analyze sequences of frames
- **Input**: 30 frames, each 160x160 in size
- **Output**: Probability of Violence / Non-Violence

---

## 📁 Folder Structure

```
├── app.py                         # Main script (Gradio UI)
├── ViolenceDetectionModel.keras  # Pre-trained Keras model (downloaded separately)
├── requirements.txt              # Python dependencies
├── README.md                     # Project documentation
```

---

## ⚙️ Installation

### 🔹 Step 1: Clone the repository
```bash
git clone https://github.com/AdeelAliYousaf/ViolenceDetectionSystem.git
cd ViolenceDetectionSystem
```

### 🔹 Step 2: Install dependencies
```bash
pip install -r requirements.txt
```

### 🔹 Step 3: Download the model
📥 [Download the pre-trained model here](https://github.com/AdeelAliYousaf/ViolenceDetectionSystem/releases/latest)  
Place the file `ViolenceDetectionModel.keras` in the root project folder.

---

## ▶️ Run the App

```bash
python app.py
```

This will open the **Gradio interface** in your browser, where you can upload a video file and receive the violence detection result.

---

## 🧪 Output Example

- **🔴 Violence Detected! (Confidence: 0.91)**
- **🟢 No Violence Detected. (Confidence: 0.12)**

---

## 💡 Use Cases

- Security and surveillance video analysis
- Violence detection in social media videos
- Smart city monitoring systems
- Research and academic projects

---

## 📌 Requirements

- Python 3.10 or 3.11
- TensorFlow 2.15
- Keras 2.15
- OpenCV (`opencv-python`)
- scikit-image
- Gradio

> Install with:
> ```bash
> pip install -r requirements.txt
> ```

---

## 🧠 Future Improvements

- 🔍 Add multi-class detection (e.g. fight, abuse, vandalism)
- 🎯 Improve model accuracy with larger datasets
- 📱 Deploy on mobile/web via TensorFlow Lite or ONNX

---

## 🧾 License

This project is licensed under the **MIT License** — use it freely, but please give credit.

---

## 🤝 Contributing

Pull requests and feedback are welcome! If you find issues or have suggestions for improvements, feel free to open an issue.

---

## 🙏 Acknowledgements

Special thanks to open-source video violence datasets and the deep learning community for their valuable contributions to safety tech research.

---
