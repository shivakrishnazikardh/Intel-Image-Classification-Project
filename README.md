# 🧠 Intel Image Classification Using CNN

## 📌 Project Overview

This project involves building and training a **Convolutional Neural Network (CNN)** using **TensorFlow** and **Keras** to classify images from the **Intel Image Classification dataset**. The model predicts six different land cover classes and evaluates its performance with metrics like classification reports and confusion matrices.

---

## 🧰 Tools & Libraries Used

| Tool/Library | Purpose |
|--------------|---------|
| `TensorFlow` & `Keras` | Building and training the CNN model |
| `Matplotlib` | Visualization of images and training progress |
| `Seaborn` | Creating the heatmap for the confusion matrix |
| `Scikit-learn (sklearn)` | Generating classification report and confusion matrix |
| `NumPy` | Handling predictions and label arrays (implicitly used in prediction processing) |
| `Intel Image Classification Dataset` | Source of training, testing, and prediction images |

---

## 📂 Dataset Structure

- `seg_train/` – Training images grouped into folders by class  
- `seg_test/` – Testing images grouped into folders by class  
- `seg_pred/` – Additional images used for prediction/visualization

---

## 🚀 Key Features

- 📁 **Image Preprocessing**:
  - Resizing to 150x150 pixels
  - Normalization
  - Data augmentation (flip, height/width variation)

- 🧠 **Model Architecture**:
  - 5 convolutional layers
  - MaxPooling after each convolution
  - Dense output with Softmax for 6-class classification

- 🧪 **Model Evaluation**:
  - Accuracy and loss tracking
  - Classification report
  - Confusion matrix heatmap
  - Visual predictions on test samples

---

## 📊 Output Classes

- `buildings`
- `forest`
- `glacier`
- `mountain`
- `sea`
- `street`

---

## 📝 How to Run

1. Set paths to the dataset directories
2. Run the script in a Python environment with necessary libraries installed
3. Review the training summary, classification performance, and visual outputs

Developed By Riakantha Shiva Krishna
