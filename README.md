
# Sign Language Converter 🤟

A deep learning-based project designed to help physically disabled individuals communicate using sign language in public spaces such as cafes and hotels. Developed as part of our **Project Based Learning (PBL)** course.

## 🧠 Project Overview

This project implements a **Sign Language Converter** using a Convolutional Neural Network (CNN). It recognizes body motion patterns associated with sign language gestures and converts them into text-based interpretations, aiding communication in real-world environments.

## 🎯 Problem Statement

Physically disabled individuals, especially those with hearing or speech impairments, face challenges in effectively communicating in public places. This project aims to bridge that communication gap by recognizing sign language gestures and translating them into readable text.

## ⚙️ Technologies Used

- **Python 3.x**
- **TensorFlow / Keras**
- **NumPy**
- **Jupyter Notebook**
- **Convolutional Neural Networks (CNN)**

## 📁 Repository Contents

- **`0.npy`**  
  Contains NumPy array data – likely preprocessed features or training input.

- **`ProzektSL+.ipynb`**  
  Initial development notebook with CNN training pipeline and gesture recognition logic.

- **`ProzektSL+_final.ipynb`**  
  Final refined notebook with complete functionality and model evaluation.

- **`pbl_final.h5`**  
  Saved trained CNN model in HDF5 format.

- **`README.md`**  
  The file you're currently reading – contains details about the project.

## 📊 Dataset

We created a custom dataset by recording the motion of body parts involved in sign language gestures. The dataset was preprocessed and formatted into NumPy arrays for use with CNN models.

## 🚀 How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/sign-language-converter.git
   cd sign-language-converter
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Open and run the final notebook:
   ```bash
   jupyter notebook ProzektSL+_final.ipynb
   ```

4. Use the saved model `pbl_final.h5` to make predictions.

## 💡 Features

- Real-time sign language recognition
- Trained on a custom dataset
- CNN-based gesture classification
- User-friendly pipeline for extension or real-time integration

## 📚 Acknowledgements

This project was created for our **Project Based Learning (PBL)** course. Special thanks to our instructors and peers for their guidance and support.

---

