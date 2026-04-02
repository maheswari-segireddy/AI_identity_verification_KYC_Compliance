<h1 align="center">Vidzai Digital</h1>
<h3 align="center">AI-Powered Identity Verification & Fraud Detection for KYC Compliance</h3>

---

This repository contains an **end-to-end AI solution** developed under **Vidzai Digital** for automating the **KYC (Know Your Customer)** process.
The system focuses on **identity verification, document validation, and fraud detection** to ensure **secure and compliant user onboarding**.

---

## 🚀 Features

### 👤 Face Detection & Matching

Utilizes deep learning techniques to detect faces and compare live images with ID documents for identity verification.

### 📄 Document Detection & OCR

Automatically identifies identity documents and extracts relevant details using Optical Character Recognition (OCR).

### 🛡️ Tamper Detection

Implements a deep learning model to identify forged or manipulated documents.

### 📍 Address Verification

Validates user-provided address details through an automated processing pipeline.

### 🌐 Integrated Frontend

Provides a simple and interactive web interface for a smooth eKYC experience.

---

## 📂 Project Structure

```
AI-Powered-Identity-Verification-and-Fraud-Detection-for-KYC-Compliance/
│
├── Face detection/              # Face recognition modules
├── document detection/          # Document processing & OCR
├── frontend/                    # Web interface
│   └── Adress_Detection.ipynb   # Address verification
│
├── tampmodeltraining.ipynb      # Tamper detection model
├── tampering dataset.ipynb      # Dataset preprocessing
│
└── README.md
```

---

## 🛠️ Tech Stack

### Programming Languages

* Python (Jupyter Notebooks)
* HTML, CSS, JavaScript

### AI / ML Frameworks

* TensorFlow / Keras or PyTorch

### Computer Vision

* OpenCV

---

## 🔧 Installation & Setup

### 1. Clone the Repository

git clone https://github.com/maheswari-segireddy/AI_identity_verification_KYC_Compliance.git
cd AI-Powered-Identity-Verification-and-Fraud-Detection-for-KYC-Compliance


### 2. Install Dependencies

```bash
pip install -r requirements.txt
```

> Note: Create `requirements.txt` based on the libraries used.

---

## 📊 Workflow Overview

1. User uploads ID document and selfie
2. System extracts data using OCR
3. Face recognition verifies identity
4. Tamper detection checks authenticity
5. Address verification validates details
6. Final verification result is generated

---

## ⚖️ License

This project is licensed under the **MIT License**.
