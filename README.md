# 🌿 AgriSense AI – AI-Powered Crop Health Analysis & Smart Farming Guidance

AgriSense AI is an intelligent plant disease detection system designed to assist farmers through fast, accurate, and accessible crop health diagnosis. The system integrates deep learning, computer vision, and an optional NLP-based advisory module to provide disease classification and smart farming guidance.

The project leverages a lightweight CNN architecture (MobileNet) to enable efficient inference even on low-resource devices, making it suitable for real-world agricultural environments.

---

## 🚀 Key Features

- 🌱 Leaf disease detection using deep learning
- ⚡ MobileNet-based lightweight architecture
- 🖼 Image preprocessing and augmentation pipeline
- 📊 Model evaluation with performance metrics
- 💬 (Optional) NLP-based advisory for farmer queries
- 📈 Data visualization for better decision-making

---

## 🧠 Model & Approach

- **Architecture:** MobileNet (lightweight CNN)
- **Dataset:** PlantVillage Dataset
- **Task:** Multi-class crop disease classification
- **Pipeline:**
  - Image preprocessing (resizing, normalization, augmentation)
  - Feature extraction using MobileNet
  - Classification layer for disease prediction
  - Model evaluation and prediction

MobileNet was chosen over heavier architectures (VGG/ResNet) due to its reduced computational cost and faster inference time.

---

## 📊 Results

- Validation Accuracy: XX%
- Test Accuracy: XX%
- Successfully classified multiple leaf diseases across different crop types.

(Add actual accuracy values from your model)

Example Prediction Output:

![Prediction Output](assets/prediction.png)

---

## ⚠️ Limitations

- Dataset primarily contains clean, controlled images (PlantVillage).
- Real-world farm images with complex backgrounds may reduce performance.
- Limited number of crop types supported.
- Web deployment may require stable internet connection.

---

## 🔮 Future Improvements

- Integration with real-world field images
- Offline mobile deployment (TensorFlow Lite)
- Multilingual NLP-based farmer guidance
- IoT sensor integration for smart farming insights

---

## 🛠 Tech Stack

- Python
- TensorFlow / Keras
- NumPy
- OpenCV
- Matplotlib
- Scikit-learn
- (Optional) NLP Transformers

---

## 📁 Repository Structure
