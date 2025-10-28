# Breast Cancer Classification Using Artificial Neural Network (ANN)

## Project Overview
This project uses an **Artificial Neural Network (ANN)** to predict whether a breast tumor is **malignant or benign** based on patient diagnostic features. The model is trained on the **Breast Cancer Dataset** from `scikit-learn` and demonstrates a practical application of neural networks in healthcare.

## Dataset
- **Source:** `sklearn.datasets.load_breast_cancer`
- **Features:** 30 numerical attributes derived from tumor cell images.
- **Target:** Binary label — `0` for malignant, `1` for benign.

## Model Architecture
- **Input Layer:** 30 features  
- **Hidden Layers:** 2 layers (16 neurons → 8 neurons) with **ReLU activation**  
- **Dropout:** 0.3 and 0.2 to reduce overfitting  
- **Output Layer:** 1 neuron with **Sigmoid activation** for binary classification

## Training Details
- **Loss Function:** Binary Crossentropy  
- **Optimizer:** Adam  
- **Metrics:** Accuracy, Precision, Recall  
- **Techniques Used:** Feature scaling, dropout, early stopping  

## Results
- High accuracy on test data with minimal overfitting  
- Precision and recall ensure reliable classification performance for both classes  

## How to Run
1. Install required packages:  
   ```bash
   pip install numpy pandas scikit-learn tensorflow matplotlib
