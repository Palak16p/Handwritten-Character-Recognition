# Handwritten Character Recognition using CNN

## Project Overview

This project focuses on recognizing handwritten digits (0–9) using a Convolutional Neural Network (CNN).

The model is trained on the MNIST dataset using TensorFlow and Keras. It learns patterns from handwritten digit images and predicts the corresponding digit.

## Objectives

- Understand handwritten digit recognition using Deep Learning.
- Explore and preprocess the MNIST dataset.
- Build and train a CNN model.
- Evaluate model performance using test accuracy and a confusion matrix.
- Test the trained model on custom handwritten digit images.

## Technologies Used

- Python
- TensorFlow and Keras
- NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook
- Pillow (PIL)
- Git and GitHub

## Dataset

**MNIST Handwritten Digits Dataset**

- Training images: 60,000
- Testing images: 10,000
- Image dimensions: 28 × 28 pixels
- Classes: 10 (digits 0–9)

## Model Architecture

A Convolutional Neural Network (CNN) was developed using:

- Convolutional layer (Conv2D)
- Max Pooling layer
- Flatten layer
- Dense layers

## Model Performance

- Test Accuracy: **98.40%**
- Evaluated using a confusion matrix.
- Tested predictions on sample MNIST images.
- Tested the trained model using custom handwritten digit images.

## Project Structure

```text
Handwritten_character_recognition/
│
├── Custom_Digit_Recognition/
│   ├── custom_digit_prediction_1.ipynb
│   └── custom_digit_test_1.ipynb
│
├── handwritten_recognition.ipynb
├── handwritten_digit_model.keras
├── my_digit.png
├── my_img1.png
├── Diary
└── .gitignore
```

## Installation and Setup

1. Clone the repository:

```bash
git clone https://github.com/Palak16p/Handwritten-Character-Recognition.git
```

2. Navigate to the project folder:

```bash
cd Handwritten-Character-Recognition
```

3. Create a virtual environment:

```bash
python -m venv .venv
```

4. Activate the environment on Windows:

```powershell
.\.venv\Scripts\Activate.ps1
```

5. Install the required libraries:

```bash
pip install tensorflow numpy matplotlib scikit-learn pillow jupyter
```

6. Open Jupyter Notebook:

```bash
jupyter notebook
```

## Future Scope

- Recognize multi-digit handwritten numbers.
- Improve custom image preprocessing.
- Explore more advanced CNN architectures.
- Develop a simple interface for handwritten digit recognition.

## Author

**Palak Patel**

Machine Learning Internship Project – CodeAlpha

## Acknowledgement

This project was developed as part of the Machine Learning Internship at CodeAlpha, with the objective of gaining practical experience in Deep Learning and image classification.
