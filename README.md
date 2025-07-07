# 🧠 E-Waste Image Classification | AICTE Internship Project

## 🌍 E-waste is surrounding the Earth, threatening our planet one device at a time.

![E-Waste Awareness](ewaste_pic.jpg)

Proper classification of e-waste enables better recycling, reduces environmental damage, and promotes sustainable technology disposal.

This project was developed as part of the **AICTE Virtual Internship Program**. It addresses the growing problem of electronic waste (e-waste) by using a deep learning model to automatically classify e-waste images into categories.

---

## 🚩 Problem Statement

The massive rise in electronic gadget usage has led to a significant increase in e-waste generation. Manual sorting is inefficient, error-prone, and costly.  
This project aims to create a system that can automatically classify images of e-waste, which supports better recycling and waste management processes.

---

## 🎯 Objectives

- Classify images of e-waste into categories such as Mobile, Printer, Keyboard, etc.  
- Build a web-based application using Streamlit to allow image upload and real-time prediction  
- Use a deep learning model (EfficientNet) for high-accuracy classification  
- Simplify the e-waste identification process for better environmental outcomes

---

## ⚙️ Tools and Technologies Used

- **Python**
- **TensorFlow / Keras** – model training and prediction  
- **PIL, NumPy** – image processing  
- **Streamlit** – web app development  
- **Google Colab / Jupyter Notebook** – model development environment

---

## 🗂️ Project Structure
e_waste/
│
├── ewaste_app.py # Streamlit web application
├── Efficient_classify.keras # Trained CNN model (EfficientNet)
├── requirements.txt # List of Python libraries
└── README.md # Project documentation

---

🖼️ App Features
Upload an image of an electronic waste item

Get real-time classification and confidence score

Supports 10 categories of e-waste including Mobile, TV, Keyboard, Mouse, PCB, etc.

Simple UI using Streamlit for easy interaction

---

📌 Note on Deployment
The model file (Efficient_classify.keras) is approximately 63 MB.
To deploy this app on Streamlit Community Cloud, it's recommended to:

Use Git Large File Storage (Git LFS)

Or host the model externally (e.g., Google Drive) and load it dynamically

---
