# Handwritten Digit Recognition using Artificial Neural Network (ANN)
# MPOnline AI&ML Internship Course assignment-8
## Tamojit Ghosh 23MIM10125 (IN26010293)

## Objective

The objective of this project is to develop an Artificial Neural Network (ANN) capable of accurately recognizing handwritten digits (0–9) from the MNIST dataset. The model is designed to automate digit classification, making it suitable for real-world applications such as postal code recognition, bank cheque processing, form digitization, and document automation. The project demonstrates the complete machine learning workflow, including data preprocessing, model development, training, evaluation, and performance visualization.

---

## Dataset Link

**Dataset:** MNIST Handwritten Digits Dataset (CSV Format)

**Kaggle:**  
https://www.kaggle.com/datasets/oddrationale/mnist-in-csv

---

## Libraries Used

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- TensorFlow
- Keras

---

## Methodology

1. Loaded the MNIST handwritten digits dataset using Pandas.
2. Explored the dataset by displaying sample records and summary information.
3. Identified input features and the target variable.
4. Checked the dataset for missing values.
5. Normalized pixel values to the range of 0–1.
6. Split the dataset into 80% training data and 20% testing data.
7. Applied One-Hot Encoding to the target labels.
8. Built and trained an Artificial Neural Network using TensorFlow/Keras.
9. Evaluated the trained model using test accuracy, confusion matrix, and classification report.
10. Visualized model performance using Accuracy vs Epoch and Loss vs Epoch graphs.

---

## ANN Architecture

| Layer | Configuration |
|--------|---------------|
| Input Layer | 784 Input Features (28 × 28 Pixels) |
| Hidden Layer 1 | 128 Neurons, ReLU Activation |
| Hidden Layer 2 | 64 Neurons, ReLU Activation |
| Output Layer | 10 Neurons, Softmax Activation |

**Model Configuration**

- **Optimizer:** Adam
- **Loss Function:** Categorical Crossentropy
- **Evaluation Metric:** Accuracy
- **Epochs:** 10
- **Batch Size:** 32

---

## Results

The Artificial Neural Network successfully learned to classify handwritten digits from the MNIST dataset with high accuracy.

The project generated the following outputs:

- Dataset exploration and summary
- Sample handwritten digit visualization
- Data preprocessing and normalization
- ANN model summary
- Training history
- Test accuracy
- Confusion Matrix
- Classification Report
- Accuracy vs Epoch graph
- Loss vs Epoch graph
- Sample digit predictions

The trained model achieved excellent classification performance, with high precision, recall, and F1-scores across all digit classes and an overall test accuracy of approximately **97–99%**.

---

## Conclusion

This project demonstrates the effectiveness of Artificial Neural Networks for handwritten digit recognition. By combining proper data preprocessing, normalization, and a multi-layer ANN architecture, the model successfully classifies handwritten digits with high accuracy. The evaluation metrics and learning curves indicate strong model performance and good convergence. Such systems can be effectively applied in postal code recognition, automated document processing, banking applications, and optical character recognition (OCR), reducing manual effort while improving speed and accuracy.
