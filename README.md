# 🖐️ Hast-Akshar: Deep Learning Based Sign Language for Devanagari

![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)
![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)
![Contributions Welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg)
![Status](https://img.shields.io/badge/status-in--progress-yellow)

## 📌 Overview

**Hast-Akshar** is a deep learning-based project that recognizes hand gestures for **Devanagari characters** (used in Hindi, Marathi, and Sanskrit). It aims to enable communication through sign language recognition, empowering the hearing and speech-impaired community by converting gestures into readable script using computer vision and neural networks.

## 🎯 Objectives

- Recognize isolated gestures representing Devanagari letters
- Build a robust gesture classification model using CNNs
- Provide real-time predictions through webcam or video input
- Set the foundation for full sentence and phrase recognition in Indian Sign Language

## 🧠 Tech Stack

- **Language:** Python  
- **Libraries:** TensorFlow / Keras or PyTorch, OpenCV, NumPy, Matplotlib  
- **Tools:** Jupyter Notebooks, Git, Scikit-learn  
- **Visualization:** Seaborn, Matplotlib

## 📁 Dataset

The dataset is custom-created and organized by Devanagari letters. Each folder contains:
- Multiple hand gesture images for each letter
- Variations in lighting, orientation, and hand shape
- Image preprocessing steps applied: resizing, grayscale conversion, normalization

> 🔒 *Note: Due to privacy or size, dataset access may be restricted. Contact the repository owner if needed.*

## ⚙️ Features

- 📷 Real-time hand gesture recognition
- 🔤 Devanagari character output display
- 📈 Model training and evaluation metrics
- 🧪 Dataset augmentation for better generalization

## 🚀 Future Scope

- 🔊 Text-to-speech conversion for full accessibility
- 🧠 Integration with NLP to recognize full sentences
- 📱 Mobile and Web App interface using Flask or React
- 🌍 Support for other Indian scripts and regional sign languages

## 🛠️ Installation

```bash
git clone https://github.com/your-username/hast-akshar.git
cd hast-akshar
pip install -r requirements.txt
```

## 🧪 Run the Model
```bash
python train_model.py    # Train the model
python recognize.py      # Run real-time recognition

```

## 🧑‍💻 Contributing
Contributions are welcome! If you want to improve this project:

- Fork the repository
- Create a new branch (git checkout -b feature-name)
- Commit your changes (git commit -m 'Add new feature')
- Push to the branch (git push origin feature-name)
- Open a Pull Request

## 📝 License
This project is licensed under the Apache License 2.0.
