# 🤖 AI-Generated vs Real Face Classification

This deep learning project aims to distinguish between **AI-generated (fake)** and **real human** facial images using a Convolutional Neural Network (CNN) model. The model is trained on high-quality datasets to help identify synthetic faces—important in fighting misinformation, deepfakes, and AI abuse.

---

## 🎯 Project Objective

With the rise of GANs and realistic face generators (like ThisPersonDoesNotExist), it becomes crucial to develop AI models that can detect whether an image is real or machine-generated.

---

## 🚀 Technologies Used

- Python
- TensorFlow / Keras
- OpenCV
- Matplotlib
- NumPy
- CNN (Convolutional Neural Network)

---

## 🗂️ Dataset Overview

- ✅ High-quality dataset of facial images
- 📂 Two classes:
  - **AI-generated faces**
  - **Real human faces**
- Dataset Source: [Kaggle Dataset](https://www.kaggle.com/datasets/xhlulu/140k-real-and-fake-faces)

---

## 🧠 Model Architecture

- Input Size: (150x150x3)
- Convolution + MaxPooling Layers
- Dropout for Regularization
- Dense Layer with Sigmoid Activation

---

## 📊 Training Results

- Training Accuracy: ~98%
- Validation Accuracy: ~96%
- Loss Curves: Stable with good generalization

---

## 🧪 Evaluation

- Confusion Matrix, Classification Report
- Real-time prediction on custom images (upload & test)
- Excellent performance on unseen image samples

---

## 🖼️ Sample Output

| Image | Prediction |
|-------|------------|
| ![real](sample_real.jpg) | Real |
| ![fake](sample_fake.jpg) | AI-generated |

*(You can add actual image examples if possible)*

---

## 📈 Future Work

- Use EfficientNet or ResNet for higher accuracy
- Implement explainable AI (Grad-CAM, LIME)
- Convert to mobile app or web dashboard
- Add live webcam detection

---

## 🤝 Author

**A.H.M. Nazmul Hasan**  
AI/ML Developer | Computer Engineer  
GitHub: [@nh30073007](https://github.com/nh30073007)

---

> 💬 *“Let’s build AI that understands AI.”*
