# CodeAlpha_Handwritten-Character-Recognition-using-CNN
# ✍️ Handwritten Character Recognition using CNN

## 📌 Project Overview

This project was developed as part of the **CodeAlpha Machine Learning Internship**.

The objective of this project is to build a **Handwritten Character Recognition System** capable of identifying handwritten digits (0–9) using **Deep Learning**. The model is trained on the **MNIST Handwritten Digits Dataset** using a **Convolutional Neural Network (CNN)** built with TensorFlow and Keras.

The trained model learns image patterns and accurately predicts handwritten digits, making it a fundamental Computer Vision application.

---

## 🎯 Objective

* Recognize handwritten digits from images.
* Learn image preprocessing techniques.
* Build a Convolutional Neural Network (CNN).
* Train and evaluate the model.
* Predict handwritten digits with high accuracy.

---

## 📂 Dataset

**Dataset:** MNIST Handwritten Digits Dataset

**Source:** TensorFlow / Keras

The dataset contains:

* **60,000** training images
* **10,000** testing images
* **28 × 28** grayscale images
* Digits from **0 to 9**

Each image belongs to one of the ten classes:

```text
0 1 2 3 4 5 6 7 8 9
```

---

## 🛠️ Technologies Used

* Python
* TensorFlow
* Keras
* NumPy
* Matplotlib
* Google Colab / Jupyter Notebook

---

## 🧠 Deep Learning Model

The project uses a **Convolutional Neural Network (CNN)** consisting of:

* Convolution Layer
* ReLU Activation
* Max Pooling Layer
* Flatten Layer
* Fully Connected (Dense) Layer
* Softmax Output Layer

---

## 📊 Project Workflow

```text
Load Dataset
      │
      ▼
Preprocess Images
      │
      ▼
Normalize Pixel Values
      │
      ▼
Reshape Images
      │
      ▼
Build CNN Model
      │
      ▼
Train Model
      │
      ▼
Evaluate Accuracy
      │
      ▼
Predict Handwritten Digits
```

---

## 📈 Model Performance

After training for **5 epochs**, the model achieves approximately:

* **Training Accuracy:** ~99%
* **Testing Accuracy:** ~98–99%

*(Accuracy may vary slightly depending on the training environment.)*

---

## 📁 Project Structure

```text
CodeAlpha_HandwrittenCharacterRecognition/
│
├── HandwrittenCharacterRecognition.ipynb
├── handwritten_character_recognition.keras
├── README.md
├── requirements.txt
├── sample_output.png
└── images/
```

---

## 🚀 How to Run the Project

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/CodeAlpha_HandwrittenCharacterRecognition.git
```

### 2. Navigate to the Project Folder

```bash
cd CodeAlpha_HandwrittenCharacterRecognition
```

### 3. Install Required Libraries

```bash
pip install tensorflow numpy matplotlib
```

### 4. Run the Notebook

Open **HandwrittenCharacterRecognition.ipynb** in **Google Colab** or **Jupyter Notebook** and execute all cells.

---

## 📷 Sample Prediction

Input Image

```text
Handwritten Digit: 7
```

Model Prediction

```text
Predicted Digit: 7
```

---

## 📚 Skills Learned

Through this project, I gained practical experience in:

* Computer Vision
* Image Processing
* Deep Learning
* Convolutional Neural Networks (CNN)
* TensorFlow & Keras
* Data Preprocessing
* Image Classification
* Model Evaluation

---

## 🔮 Future Enhancements

* Recognize handwritten alphabets using the EMNIST dataset.
* Build a web application using Streamlit or Flask.
* Deploy the trained model on the cloud.
* Extend the model to recognize complete handwritten words and sentences.
* Improve performance using advanced CNN architectures.

---

## 👩‍💻 Author

**Dharshini S**

B.E. Computer Science and Engineering

Machine Learning Enthusiast | Aspiring Data Scientist

---
---

## ⭐ If you found this project helpful, please consider giving it a star!
