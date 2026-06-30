# Quantum Image Classifier using QCNN

An advanced image processing and classification framework that leverages Hybrid Quantum-Classical Machine Learning to segregate and classify complex textual images. This project implements a **Quantum Convolutional Neural Network (QCNN)** built using **PennyLane** to perform high-efficiency binary classification.

*This project was developed as part of an **Internship at IIIT Kottayam**.*

---

## 📌 Project Overview
The core goal of this project is to distinguish and categorize textual characters into two distinct structural formats:
1. **Ancient Characters** (`Ancient_Non_OBC`)
2. **Modern Kanji Characters** (`Modern_Kanji`)

By utilizing a Quantum Convolutional Neural Network (QCNN), the framework introduces quantum circuits capable of representation learning, executing quantum convolution and pooling operations to detect feature hierarchies that classical networks might struggle to parse efficiently.

---

## 🛠️ Technical Workflow

### 1. Data Cleaning & Automated Segregation
Before feeding images into the quantum pipeline, the workspace cleans up old allocations and handles unstructured datasets directly from zip formats. It walks through nested directories to isolate images with standard formats (`.png`, `.jpg`, `.jpeg`, etc.), renaming and centralizing them into a structured directory tree:
```text
dataset_segregated/
   ├── Ancient_Non_OBC/  --> (Centralized ancient image samples)
   └── Modern_Kanji/     --> (Centralized modern Kanji image samples)
