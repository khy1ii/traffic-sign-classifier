# Traffic Sign Image Classifier 🚦

A CNN-based traffic sign image classifier built using TensorFlow, OpenCV, NumPy, and Pandas on the German Traffic Sign Recognition Benchmark (GTSRB) dataset.

This project demonstrates a complete computer vision workflow including image preprocessing, model training, evaluation, and visualization using Jupyter Notebook.

---

# 📌 Features

- Traffic sign image classification using Convolutional Neural Networks (CNNs)
- Image preprocessing and normalization using OpenCV
- Data handling using Pandas and NumPy
- Model training and validation using TensorFlow/Keras
- Accuracy and loss visualization
- Confusion matrix evaluation
- Jupyter Notebook workflow

---

# 🛠 Technologies Used

- Python
- TensorFlow / Keras
- OpenCV
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
- Seaborn
- Jupyter Notebook

---

# 📂 Dataset

Dataset Used:
German Traffic Sign Recognition Benchmark (GTSRB)

Kaggle Dataset:
https://www.kaggle.com/datasets/meowmeowmeowmeowmeow/gtsrb-german-traffic-sign

---

# 🧠 Model Architecture

The CNN architecture consists of:

- Conv2D Layers
- MaxPooling Layers
- Flatten Layer
- Dense Layers
- Softmax Output Layer

Input Image Size:
32 x 32 x 3

Number of Classes:
43

---

# 📊 Results

## Validation Accuracy
97.78%

---

## Accuracy Graph

![Accuracy Graph](images/accuracy.png)

---

## Loss Graph

![Loss Graph](images/loss.png)

---

## Confusion Matrix

![Confusion Matrix](images/confusion_matrix.png)

---

# 📈 Workflow

1. Load dataset metadata using Pandas
2. Perform exploratory data analysis
3. Preprocess images using OpenCV
4. Resize images to 32x32
5. Normalize pixel values
6. Convert images into NumPy arrays
7. Split dataset into training and validation sets
8. Train CNN model using TensorFlow/Keras
9. Evaluate model performance using:
   - Accuracy and Loss Graphs
   - Confusion Matrix
   - Validation Metrics

---

# 🎯 Key Learnings

- Computer vision preprocessing techniques
- CNN architecture fundamentals
- TensorFlow/Keras model training
- Model evaluation and visualization
- Data normalization and preprocessing pipelines
- Validation and overfitting analysis

---

# 🔮 Future Improvements

- Real-time webcam prediction
- Data augmentation
- Transfer learning models
- Flask or Streamlit deployment
- Traffic sign detection pipeline

---

# 👨‍💻 Author

Egr. Khyle R. Monterola, ECT
