# Digit Recognition Model 🧠✏️

A simple neural network built with **TensorFlow/Keras** to recognize handwritten digits from the **MNIST dataset**.

---

## 📂 Project Structure
- **Assignment_1_Digit_Recognition.ipynb** → Jupyter Notebook containing all code for loading data, building, training, and evaluating the model.
- **README.md** → Project description and usage instructions.

---

## 🚀 Model Overview
- **Input Layer:** Flattened 28×28 pixel grayscale images (784 features).
- **Hidden Layer:** Dense layer with 100 neurons, ReLU activation.
- **Output Layer:** Dense layer with 10 neurons, Sigmoid activation (digits 0–9).
- **Loss Function:** Sparse Categorical Crossentropy.
- **Optimizer:** Adam.
- **Metric:** Accuracy.

---

## 🏃‍♂️ How to Run
1. Install dependencies:
   ```bash
   pip install tensorflow matplotlib seaborn
