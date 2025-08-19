#  Price prediction using Neural Network with LSTM, Hybrid LSTM-SVM, and QLSTM 

This repository contains part of an M.Sc. Statistics project focused on predictive modeling using advanced neural architectures. It showcases three models: a recurrent LSTM, a hybrid LSTM-SVM, and an experimental quantum-inspired LSTM (QLSTM).

---

##  Overview

The goal of this project is to implement and compare different neural network architectures for predictive modeling. The models here demonstrate how classical deep learning methods can be extended with hybrid and quantum techniques to capture complex patterns in data.

---

##  Models Implemented

This repository contains the following models:

1. **LSTM (Long Short-Term Memory):**  
   A recurrent neural network designed to capture long-term dependencies in sequential or structured data.

2. **Hybrid LSTM-SVM:**  
   Combines the feature extraction capabilities of LSTMs with the classification strength of Support Vector Machines (SVM). LSTM hidden states are used as input features for an SVM with RBF kernel.

3. **QLSTM (Quantum LSTM):**  
   An experimental model that replaces classical weight matrices in LSTM cells with Variational Quantum Circuits (VQCs). Implemented using PennyLane to simulate quantum layers.

---

##  Features

- **Sequential/Structured Data Modeling** with LSTMs.  
- **Hybrid Approach** combining deep learning (LSTM) with classical ML (SVM).  
- **Quantum Machine Learning** using PennyLane for quantum circuit simulations.  
- **Data Preprocessing** with normalization and feature scaling.  
- **Visualization** of results with plots of accuracy and loss.  

---

##  Technology Stack

- **Python 3.x**  
- **PyTorch** – for LSTM and QLSTM implementations  
- **PennyLane** – for quantum circuit simulation in QLSTM  
- **Scikit-learn** – for SVM, preprocessing, and evaluation  
- **NumPy / Pandas** – for data manipulation  
- **Matplotlib** – for visualization  

---

##  Getting Started

### Prerequisites
- Python 3.8+  
- A virtual environment is recommended  

### Installation
```bash
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
pip install -r requirements.txt
