# Alzheimers-Prediction-Using-EfficientNetB3
This project uses Convolutional Neural Networks (CNNs) to classify Alzheimer's disease stages from MRI scans using TensorFlow and Keras.
📌 You can download similar datasets from [Kaggle](https://www.kaggle.com/datasets/tourist55/alzheimers-dataset-4-class-of-images) or Mendeley Data.

## 🧠 Model

- CNN with multiple Conv2D and MaxPooling layers
- Dropout and BatchNormalization for regularization
- Trained using Adam optimizer and Categorical Crossentropy

## 📊 Evaluation

The model performance is visualized using accuracy and loss plots over training and validation sets.

## 📂 Files

- `your_model1.h5`: Trained CNN model
- `training_history1.pkl`: Training history object
- `code.ipynb`: Jupyter notebook with full pipeline

## 🚀 How to Run

1. Clone the repository or upload to Google Colab.
2. Mount Google Drive to access the dataset and model files.
3. Run all cells in `code.ipynb`.
