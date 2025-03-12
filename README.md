# 🧠 Brain Tumor Detection Using Deep Learning  and GAN for data generation

## 📌 Overview  
This project focuses on **detecting brain tumors** using **deep learning techniques**. The model is trained on MRI scan images to classify into 4 categories: Glioma, Meningioma, Pituitary or No Tumor. The **Convolutional Neural Network (CNN)** architecture is used for image classification, ensuring accurate tumor detection. Implemented **GAN** for creating new data to overcome imbalanced dataset and generalization to new data.

## 🚀 Features  
✅ Automated brain tumor classification using deep learning.  
✅ Trained on MRI scan images for high accuracy.  
✅ Uses **TensorFlow/Keras** for model training.   

## 📂 Dataset  
- The dataset consists of MRI images labeled as **pituitary**, **meningioma**, **glioma** or **no tumor**.  
- Data preprocessing includes **image resizing, normalization, and augmentation**.  

## 🏗️ Model Architecture  
- **Convolutional Layers (CNN)** extract spatial features.  
- **Pooling Layers** reduce dimensionality.  
- **Fully Connected Layers** for classification.  
- **Activation Function**: `ReLU` (hidden layers), `Softmax` (output layer).  

## 🔧 Installation & Setup  
1️⃣ Clone the repository:  
```bash
git clone https://github.com/argorrepati01/brain-tumor-detection.git
cd brain-tumor-detection
