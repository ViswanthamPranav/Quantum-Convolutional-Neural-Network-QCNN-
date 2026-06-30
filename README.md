# Quantum Image Classifier

This project implements a **Quantum Convolutional Neural Network (QCNN)** using **PennyLane** to classify and segregate images into two categories: Ancient Characters and Modern Kanji Characters.

This project was developed during my **Internship at IIIT Kottayam**.

## 📂 Project Structure
* `finalest_final_qcnn_segregation_code.ipynb` - The main Google Colab / Jupyter Notebook containing the data pipeline and Quantum Machine Learning models.
* `dataset_ancient_modern (1).zip` - The raw image dataset used for training and classification.

## 🛠️ How It Works
1. **Data Preprocessing:** The notebook automatically unzips the dataset, cleans up old directories, and structures images into categorized folders (`Ancient_Non_OBC` and `Modern_Kanji`).
2. **Quantum Feature Embedding:** Image data is reduced in dimensionality so it can be loaded onto quantum qubits.
3. **QCNN Model:** Uses parameterized quantum convolution and pooling layers built on PennyLane to classify the images.

## ⚙️ Requirements
To run the notebook locally, you need the following Python libraries installed:
```bash
pip install pennylane numpy matplotlib scipy autograd
