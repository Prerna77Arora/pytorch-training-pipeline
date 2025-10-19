# Breast Cancer Prediction using PyTorch (Learning Project)

## 🧠 Project Overview
This project demonstrates the process of building a simple **Neural Network from scratch using PyTorch** for **Breast Cancer Prediction**.  
The primary goal of this project was **to understand and implement the PyTorch training pipeline**, including:
- Data loading and preprocessing  
- Model creation and forward propagation  
- Loss computation and backpropagation  
- Parameter updates using gradient descent

---

## 📊 Dataset
The dataset used in this project is the **Breast Cancer Wisconsin (Diagnostic) dataset**, loaded from the following source:  
[https://github.com/gscdit/Breast-Cancer-Detection](https://github.com/gscdit/Breast-Cancer-Detection)

**Key steps:**
- Dropped unnecessary columns (`id`, `Unnamed: 32`)
- Encoded categorical labels (Malignant/Benign)
- Scaled features using `StandardScaler`
- Split data into train/test sets (80/20)

---

## 🧩 Model Architecture
A simple neural network implemented from scratch without using `torch.nn.Module`:
- **Input Layer:** Based on number of features in dataset  
- **Output Layer:** Single neuron with **Sigmoid activation**  
- **Loss Function:** Binary Cross-Entropy  
- **Optimizer:** Manual parameter updates using gradient descent

---

## 🚀 Training Pipeline
1. Forward Pass — Compute predictions using sigmoid activation  
2. Loss Calculation — Using binary cross-entropy formula  
3. Backward Pass — Compute gradients with respect to weights and bias  
4. Parameter Update — Using manually defined learning rate  
5. Repeat for multiple epochs  

During training, the loss is printed at each epoch.

---

## 📈 Evaluation
After training, the model predicts on the test set, and accuracy is computed using a threshold (0.9).

**Output Example:**
```
Epoch: 25, Loss: 0.1432
Accuracy: 0.94
```

---

## 🧰 Technologies Used
- Python  
- NumPy  
- Pandas  
- Scikit-learn  
- PyTorch  

---

## 🎯 Learning Outcomes
- Understood how **PyTorch tensors** work for model parameters  
- Learned **manual gradient updates** and **loss computation**  
- Implemented a **basic end-to-end training pipeline** without using high-level PyTorch modules  

---

## 📁 File Structure
```
breastcancerprediction.py   # Main project file containing data prep, model, and training loop
README.md                   # Project documentation
```

---

## 👩‍💻 Author
**Prerna**  
Learning PyTorch Training Pipeline | BTech CSE | Rajiv Gandhi Institute of Petroleum Technology
