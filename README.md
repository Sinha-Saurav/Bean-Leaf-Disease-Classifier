# 🌱 Bean Leaf Disease Classifier

A deep learning–based web app built with **PyTorch** and **Streamlit** to classify bean leaf images into three categories:

- **Angular Leaf Spot**
- **Bean Rust**
- **Healthy Leaf**

This tool can help farmers and researchers quickly identify common bean leaf diseases from simple images.

---

## 🌍 Live Website
URL - https://bean-leaf-disease-classifier.streamlit.app/ 

---

## ⚙️ Features
- 🧠 **Transfer Learning with GoogLeNet**  
- 🎯 Fine-tuned on a custom dataset of bean leaves (~1,200 images, ~400 per class)  
- 📸 Upload leaf images directly through the app  
- ✅ Predicts the disease class with confidence  
- ⚡ Easy to run locally or deploy on Streamlit Cloud  

---

## 📂 Project Structure
bean-leaf-classifier/
-> app.py # Streamlit app
-> classname.txt # List of class names
-> googlenet_model.pth # Trained model weights
-> requirements.txt # Python dependencies
-> transfer_learning(CNN).pynb # Notebook
-> README.md # Project documentation


---

## 🚀 How to Run Locally

### 1. Clone the repository
```bash
git clone https://github.com/Sinha-Saurav/bean-leaf-classifier.git
cd bean-leaf-classifier
```
### 2. Install Dependencies
pip install -r requirements.txt

### 3. Run the Streamlit App
Streamlit run app.py
