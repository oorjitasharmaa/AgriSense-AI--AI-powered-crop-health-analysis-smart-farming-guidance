# AgriSense AI – AI-powered Crop Health Analysis & Smart Farming Guidance

AgriSense AI is an intelligent plant disease detection system that helps users identify crop leaf diseases from images using a lightweight deep learning model (MobileNet). The goal is fast and accessible diagnosis for smart farming.

---

## ✨ Key Features
- 🌿 Leaf disease detection from uploaded images (PlantVillage dataset)
- ⚡ Lightweight MobileNet architecture for faster inference on low-resource devices
- 🧪 Preprocessing + training + evaluation pipeline (in notebook)
- 📄 Includes research paper/report for full project explanation

---

## 🧠 Model & Approach
- **Architecture:** MobileNet (lightweight CNN)
- **Task:** Multi-class plant disease classification from leaf images
- **Dataset:** PlantVillage (public dataset of healthy/diseased leaf images)
- **Pipeline:** Data loading → preprocessing/augmentation → training → evaluation → prediction

---

## 📁 Repository Contents
- `AgriSense - AI.ipynb` — full training + prediction workflow
- `AgriSense AI research paper.pdf` — project report / documentation
- `.gitignore` — ignores unnecessary files

---

## 🚀 How to Run (Local)
### 1) Clone the repo
```bash
git clone https://github.com/oorjitasharmaa/AgriSense-AI--AI-powered-crop-health-analysis-smart-farming-guidance.git
cd AgriSense-AI--AI-powered-crop-health-analysis-smart-farming-guidance
