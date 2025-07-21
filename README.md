# Road Sign Classification using CNN 🚦🧠

This project is a deep learning-based solution for **traffic sign recognition**, built as part of the **DAT 494 capstone project**. The model uses **Convolutional Neural Networks (CNNs)** to classify images of road signs into their respective categories with high accuracy.

---

## 📌 Objective

To develop an image classification model that can:
- Accurately identify traffic signs from images
- Generalize well to unseen data
- Support future integration with autonomous vehicle systems or driver-assistance tools

---

## 🛠️ Tools & Technologies

- **Python** (Jupyter Notebook)
- **TensorFlow / Keras** – Model building & training
- **OpenCV / PIL** – Image preprocessing
- **NumPy, Pandas, Matplotlib** – Data handling & visualization
- **Scikit-learn** – Evaluation metrics

---

## 🧠 Approach

1. **Data Preprocessing**  
   - Normalization, resizing, and label encoding  
   - Visual inspection of sample images

2. **Model Architecture**  
   - Sequential CNN with Conv2D, MaxPooling, Dropout, and Dense layers  
   - Compiled with categorical cross-entropy loss and Adam optimizer

3. **Training & Evaluation**  
   - Train-validation split (e.g., 80/20)
   - Performance monitored via accuracy and loss curves
   - Final model evaluated on unseen test data

4. **Results**  
   - Achieved high validation accuracy with minimal overfitting
   - Confusion matrix and classification report included

---

