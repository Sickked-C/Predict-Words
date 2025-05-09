# ✍️ Handwriting Recognition from File using Bi-directional LSTM

This project focuses on **recognizing handwritten text from a specified file** using deep learning techniques. It demonstrates the process of loading image-based text data, preprocessing it, and training a **Bi-directional LSTM (Long Short-Term Memory)** model to accurately predict handwritten words.

## 📁 Files in This Repository

- `APP.ipynb`:  
  Main notebook that includes:
  - Loading and preprocessing data
  - Applying image processing (e.g., resizing, grayscale, normalization)
  - Creating training sequences and labels
  - Defining and training a Bi-directional LSTM model
  - Predicting and decoding recognized words from the model

- `data.txt`:  
  [🔗 Link to dataset or file reference](https://www.kaggle.com/datasets/mfekadu/darpa-timit-acousticphonetic-continuous-speech)  
  *(This file contains a link or path to the input data used for model training.)*

## 🎯 Objectives

- Preprocess handwritten image data for model training.
- Train a sequence model using Bi-directional LSTM for character or word recognition.
- Predict and output clean textual results.

## 🧠 Techniques & Tools Used

- **Image Preprocessing**: OpenCV (grayscale, resize, normalization)
- **Model Architecture**: Bi-directional LSTM built with TensorFlow/Keras
- **Text Decoding**: CTC (Connectionist Temporal Classification) loss for alignment-free learning
- **Other Tools**: NumPy, Matplotlib for visualization

## 📊 Model Highlights

- Uses **Bi-directional LSTM** to capture context from both directions in text sequences.
- Suitable for sequence prediction tasks like OCR and handwritten text recognition.
- Handles variable-length sequences using CTC loss.

## 🛠️ Requirements

```bash
pip install numpy opencv-python matplotlib tensorflow
```
---
## ▶️ How to Run
 Clone the repository:
```bash

git clone https://github.com/Sickked-C/Predict-Words.git
cd Predict-Words
```

Run the notebook:
 - Open APP.ipynb in Jupyter or Colab.
 - Train the model and evaluate its predictions.

---
## 📌 Notes
Make sure the image data is properly preprocessed (normalized and resized).

You can modify the architecture or training parameters in  `APP.ipynb` to experiment with performance.

---
## 👨‍💻 Author
Sickked-C

---
## 📝 License
This project is licensed under the MIT License.
