# MNIST-Digit-Classification-using-Neural-Network
# 🔢 Handwritten Digit Classification using Neural Network (MNIST)

## 📌 Overview
This project focuses on building a neural network model to classify handwritten digits (0–9) using the MNIST dataset.

The model learns patterns from grayscale images and predicts the correct digit.

---

## 📊 Dataset
- MNIST dataset
- 70,000 grayscale images (28x28 pixels)
- 10 classes (digits 0–9)

---

## ⚙️ Technologies Used
- Python
- TensorFlow / Keras
- NumPy
- Matplotlib

---

## 🔍 Key Steps & Work Done

### 1. Data Loading
- Loaded dataset using Keras built-in datasets
- Split into training and testing sets

---

### 2. Data Preprocessing
- Normalized pixel values (0–255 → 0–1)
- Flattened images (28x28 → 784 input features)
- Converted labels using one-hot encoding

---

### 3. Model Building
- Built a Fully Connected Neural Network (FCNN):
  - Input layer (784 neurons)
  - Hidden layers with ReLU activation
  - Output layer with Softmax (10 classes)

---

### 4. Model Compilation
- Loss: Categorical Crossentropy
- Optimizer: Adam / SGD
- Metric: Accuracy

---

### 5. Model Training
- Trained on training dataset
- Used validation data to monitor performance

---

### 6. Model Evaluation
- Evaluated model on test dataset
- Measured classification accuracy

---

### 7. Visualization
- Plotted:
  - Training vs Validation Accuracy
  - Training vs Validation Loss
- Displayed:
  - Sample digit images
  - Predicted vs actual labels

---

## 📈 Results
- Model successfully classified handwritten digits
- Achieved high accuracy on test dataset



---

## 📷 Visualizations
- Accuracy graph
- Loss graph
- Sample digit predictions

---

## 🚀 Future Improvements
- Use CNN for higher accuracy
- Add dropout layers to reduce overfitting
- Hyperparameter tuning
- Deploy using Streamlit or Flask

---

## 🔗 Project Structure
mnist-digit-classification/
│
├── MNIST_digit_classification_NN.ipynb
├── README.md


---

## 👨‍💻 Author
Saksham Goel  
Aspiring AI Engineer
