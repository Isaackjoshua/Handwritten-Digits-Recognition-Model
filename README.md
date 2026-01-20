
````markdown
# Handwritten Digits Recognition Model

This project implements a **Handwritten Digits Recognition** system using **Logistic Regression** trained on the **MNIST dataset** via **scikit-learn**.  
The goal is to demonstrate a simple yet effective classical machine learning approach to image classification.

---

## 📌 Project Overview

Handwritten digit recognition is a classic machine learning problem where the task is to classify grayscale images of digits (0–9).  
In this project, Logistic Regression is used as a baseline model to understand how linear classifiers perform on image data.

---

## 🧠 Model Used
- **Algorithm:** Logistic Regression (Multinomial)
- **Framework:** scikit-learn
- **Dataset:** MNIST (28×28 grayscale digit images)
- **Classes:** Digits 0 through 9

---

## 📂 Dataset
The **MNIST dataset** is loaded directly using `sklearn.datasets`.  
It contains:
- 70,000 images of handwritten digits
- 60,000 training samples
- 10,000 test samples
- Each image is flattened into a 784-dimensional feature vector

---

## ⚙️ Technologies & Tools
- Python
- NumPy
- scikit-learn
- Matplotlib (for visualization)

---

## 🚀 How It Works
1. Load the MNIST dataset
2. Normalize pixel values
3. Split data into training and testing sets
4. Train a Logistic Regression classifier
5. Evaluate the model using accuracy and classification metrics
6. Test predictions on sample digit images

---

## 📊 Model Evaluation
The model is evaluated using:
- Accuracy score
- Confusion matrix
- Classification report (precision, recall, F1-score)

Despite its simplicity, Logistic Regression performs reasonably well on MNIST and serves as a strong baseline model.

---

## ▶️ Installation & Usage

### Clone the Repository
```bash
git clone https://github.com/Isaackjoshua/Handwritten-Digits-Recognition-Model.git
cd Handwritten-Digits-Recognition-Model
````

### Install Dependencies

```bash
pip install numpy scikit-learn matplotlib
```

### Run the Model

```bash
python main.py

*(Adjust the filename if your script name is different)*

---

## 📈 Results

* Achieves competitive accuracy for a linear classifier
* Demonstrates how classical ML algorithms can still be effective for image classification tasks
* Useful as a learning foundation before moving to deep learning models like CNNs

---

## 🔮 Future Improvements

* Use Convolutional Neural Networks (CNNs) for higher accuracy
* Apply dimensionality reduction (PCA)
* Hyperparameter tuning
* Deploy as a web or desktop application

---

## 🤝 Contributing

Contributions, suggestions, and improvements are welcome.
Feel free to fork the repository and submit a pull request.

---

## 📜 License

This project is licensed under the MIT License.

---

## 👤 Author

**Isaack Joshua**
Bachelor of Science in Computer Science
GitHub: [https://github.com/Isaackjoshua](https://github.com/Isaackjoshua)

