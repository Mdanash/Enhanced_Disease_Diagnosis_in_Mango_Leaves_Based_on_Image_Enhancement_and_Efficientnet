# Enhanced_Disease_Diagnosis_in_Mango_Leaves_Based_on_Image_Enhancement_and_Efficientnet

This project aims to develop a deep learning-based system for detecting and diagnosing diseases in mango leaves using advanced image enhancement techniques and the EfficientNetB0 model. The system is deployed as an interactive web-based chatbot using Gradio on Hugging Face Spaces.

## 🚀 Project Highlights

- 🌿 Disease detection for mango leaves with high accuracy
- 🧠 Uses EfficientNetB0 for lightweight, efficient classification
- 🖼️ Includes image enhancement: noise reduction, sharpening, and contrast improvement
- 💬 Web-based chatbot built using Gradio for real-time interaction
- 🧪 Trained on Mango Leaf Disease Dataset with 8 classes
- 📈 Evaluation with confusion matrix, classification report, and Grad-CAM visualizations

---

## 📂 Dataset

- **Source**: [Kaggle – Mango Leaf Disease Dataset](https://www.kaggle.com/datasets/warcoder/mango-leaf-disease-dataset)
- **Classes**:
  - Anthracnose
  - Bacterial Canker
  - Cutting Weevil
  - Die Back
  - Gall Midge
  - Healthy
  - Powdery Mildew
  - Sooty Mould

---

## 🛠️ Tech Stack

- Python
- TensorFlow / Keras
- EfficientNetB0
- OpenCV (for image enhancement)
- Gradio (for UI)
- Hugging Face Spaces (for deployment)

---

## 📌 Project Workflow

1. **Image Acquisition** – Load images from the dataset.
2. **Image Enhancement** – Apply techniques like sharpening, noise reduction, and histogram equalization.
3. **Model Training** – Train EfficientNetB0 on enhanced images.
4. **Model Evaluation** – Evaluate using metrics like F1-score, accuracy, confusion matrix.
5. **Web Deployment** – Deploy as an interactive chatbot using Gradio + Hugging Face.

---

## 🧠 Model Architecture

- **EfficientNetB0**: A scalable and efficient CNN model
- **Input Shape**: 224x224x3
- **Loss**: Categorical Crossentropy
- **Optimizer**: Adam
- **Metrics**: Accuracy, F1-score

---

## 🖼️ Screenshots

![Screenshot 2](https://github.com/user-attachments/assets/7fdf53f6-7af7-4e45-b4dd-49283df05c15)
![Screenshot 1](https://github.com/user-attachments/assets/ee6ca28d-b1af-4846-90e3-9d6121352a46)


---

## 🖼️ Live Demo

- **Source**: [HuggingFace](https://huggingface.co/spaces/mohamedanash2004/mango-leaf-disease-prediction)


## 📊 Evaluation

- Classification report for each class
- Confusion matrix
- Grad-CAM heatmaps for visual interpretability

---

