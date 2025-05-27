
# Sign Language Detector 🤟  
This repository contains the code and resources for a **Sign Language Detector** project developed as part of our **Project Based Learning (PBL)** course in college.

## 📁 Repository Contents

- **`0.npy`**  
  A NumPy file that likely contains preprocessed data or feature arrays used for training or inference.

- **`ProzektSL+.ipynb`**  
  Initial version of the Jupyter Notebook used to develop and test the sign language recognition model.

- **`ProzektSL+_final.ipynb`**  
  Final refined Jupyter Notebook with the complete pipeline including data preprocessing, model training, evaluation, and testing.

- **`pbl_final.h5`**  
  The trained Keras model saved in HDF5 format. This model is used to recognize sign language gestures.

- **`README.md`**  
  You’re reading it! This file explains the contents and purpose of the repository.

## 📌 Project Objective

To build a deep learning model that detects and recognizes hand gestures representing **Indian Sign Language (ISL)** alphabets or symbols. The main goal is to support accessibility for the hearing and speech-impaired community.

## 🚀 Features

- Hand gesture classification using deep learning
- Trained on preprocessed image/feature data
- Real-time prediction potential using the saved `.h5` model
- Developed entirely in Python using TensorFlow/Keras and NumPy

## 🛠️ Technologies Used

- Python 3.x
- NumPy
- TensorFlow / Keras
- Jupyter Notebook

## 🧪 How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/sign-language-detector.git
   cd sign-language-detector
   ```

2. Install dependencies (recommended to use a virtual environment):
   ```bash
   pip install -r requirements.txt
   ```

3. Run the notebook:
   ```bash
   jupyter notebook ProzektSL+_final.ipynb
   ```

4. Use the trained model `pbl_final.h5` for predictions.

> ⚠️ Note: Ensure the correct input format as expected by the model (as defined in the notebook).

## 📚 Acknowledgements

This project was created as part of the **Project Based Learning (PBL)** course at our college. We thank our mentors and peers for their support and feedback.
