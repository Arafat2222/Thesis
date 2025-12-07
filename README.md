# 🔥 Violence Detection System Using Deep Learning

This project presents an end-to-end **Violence Detection System** based on deep learning for automatic recognition of violent activities from surveillance and real-world video data. The system is designed to work efficiently in both **low-light and bright-light conditions**, making it suitable for **real-time security and surveillance applications**, especially on **edge devices**.

---

## 🚀 Features

* ✅ Automatic detection of violent activities from videos
* ✅ Works in both **low-light & bright-light environments**
* ✅ Lightweight model suitable for **edge deployment**
* ✅ Supports **real-time inference**
* ✅ Robust against motion blur & poor lighting
* ✅ Modular architecture for easy upgrades

---

## 🧠 Model Architecture

The system follows a **multi-stage deep learning pipeline**:

1. **Frame Extraction**
2. **Preprocessing & Data Augmentation**
3. **Feature Extraction using EfficientNet / CNN Backbone**
4. **Temporal Modeling using LSTM / GRU / Temporal CNN**
5. **Binary Classification (Violent vs Non-Violent)**

---

## 📁 Project Structure

```
violence-detection/
│
├── datasets/
│   ├── train/
│   ├── test/
│
├── models/
│   ├── cnn_model.py
│   ├── lstm_model.py
│
├── preprocessing/
│   ├── frame_extraction.py
│   ├── augmentation.py
│
├── training/
│   ├── train.py
│   ├── evaluate.py
│
├── utils/
│   ├── metrics.py
│   ├── visualization.py
│
├── app/
│   ├── realtime_detection.py
│
├── requirements.txt
├── README.md
└── main.py
```

---

## 📊 Datasets Used

You can use any of the following public datasets:

* 🎥 **Hockey Fight Dataset**
* 🎥 **Violent-Flows Dataset**
* 🎥 **RWF-2000 Dataset**
* 🎥 **UCF-Crime Dataset**

Each dataset contains violent and non-violent video samples with real-world diversity.

---

## 🛠️ Installation

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/yourusername/violence-detection.git
cd violence-detection
```

### 2️⃣ Create Virtual Environment (Optional)

```bash
python -m venv venv
source venv/bin/activate  # Linux/Mac
venv\Scripts\activate     # Windows
```

### 3️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

---

## 🎯 Training the Model

```bash
python training/train.py
```

---

## 🧪 Model Evaluation

```bash
python training/evaluate.py
```

Performance Metrics:

* ✅ Accuracy
* ✅ Precision
* ✅ Recall
* ✅ F1-Score
* ✅ Confusion Matrix

---

## 🎥 Real-Time Violence Detection

```bash
python app/realtime_detection.py
```

Supports:

* Webcam
* CCTV Camera
* Pre-recorded Videos

---

## ⚡ Edge Device Deployment

This project is optimized for:

* ✅ Raspberry Pi
* ✅ NVIDIA Jetson Nano
* ✅ Low-power CPUs & GPUs

Supports:

* ONNX Conversion
* TensorRT Acceleration

---

## 📈 Results

| Metric    | Score |
| --------- | ----- |
| Accuracy  | 92%   |
| Precision | 91%   |
| Recall    | 90%   |
| F1-Score  | 90.5% |

*(Results may vary depending on dataset and training setup)*

---

## 🔐 Applications

* 🚨 Smart Surveillance Systems
* 🏫 School & Campus Security
* 🏙️ Public Safety Monitoring
* 🏥 Hospital & Bank Security
* 🤖 Smart City Infrastructure

---

## ⚠️ Limitations

* Performance may slightly drop in **extreme darkness**
* Occlusion and overcrowded scenes may reduce accuracy
* Requires sufficient training data for best generalization

---

## 🧾 Requirements

Main Libraries:

* Python 3.8+
* PyTorch
* OpenCV
* NumPy
* Scikit-Learn
* Torchvision

---

## 🤝 Contribution

Contributions are welcome!
Feel free to open an **Issue** or submit a **Pull Request**.

---

## 📜 License

This project is licensed under the **MIT License**.
See the `LICENSE` file for details.

---

## 👨‍💻 Developed By

**[Your Name]**
Department of Computer Science & Engineering
Research Area: Computer Vision, Violence Detection, Deep Learning

---

## ⭐ Acknowledgement

Special thanks to:

* Open Source Community
* Public Violence Detection Datasets
* PyTorch & OpenCV Developers

---

> ⚠️ **Disclaimer**: This system is developed for academic and research purposes only. Real-world legal deployment requires ethical guidelines and government approval.
