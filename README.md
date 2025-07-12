# Face_Mask_Detection

This is a real-time face mask detection system built using **MobileNetV2**, **TensorFlow**, and **OpenCV**. It classifies whether a person is wearing a mask or not using live webcam input.

---

## 📌 Features

- 🔍 Real-time face detection using Haar Cascades and OpenCV
- 😷 Face mask classification using pre-trained **MobileNetV2**
- 📈 Achieved ~95% classification accuracy on validation data
- 🧠 Lightweight and optimized for deployment on edge devices
- 💡 Easy to extend with your own dataset

---

## 🛠 Tech Stack

- **Language:** Python
- **Libraries:** TensorFlow, Keras, OpenCV, NumPy
- **Model:** MobileNetV2 (Transfer Learning)
- **Other Tools:** Matplotlib, scikit-learn

---

## 🧪 How It Works

1. Pre-processes input face images using OpenCV
2. Uses MobileNetV2 for binary classification (`Mask` vs `No Mask`)
3. Displays results live via webcam with bounding boxes and labels

---

## 🚀 How to Run

1. Clone the repo:
   ```bash
   git clone https://github.com/chithiraijothi07/Face_Mask_Detection.git
   cd Face_Mask_Detection
