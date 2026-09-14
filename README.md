# Real vs AI-Generated Image Classification

A PyTorch deep learning project designed to perform binary classification distinguishing between authentic real photographs and AI-generated synthetic images.

## 📌 Overview
With the rise of generative AI models, distinguishing between real images and synthetically generated content is critical. This project implements a custom Convolutional Neural Network (CNN) in PyTorch to classify images as either **REAL** or **FAKE**.

## 📊 Dataset
This project utilizes the **CIFAKE: Real and AI-Generated Synthetic Images** dataset:
- **Source:** [Kaggle Dataset Link](https://www.kaggle.com/datasets/birdy654/cifake-real-and-ai-generated-synthetic-images)
- **Real Images:** 60,000 images from CIFAR-10
- **Fake Images:** 60,000 synthetic images generated via Stable Diffusion v1.4
- **Train Set:** 100,000 images (50,000 Real / 50,000 Fake)
- **Test Set:** 20,000 images (10,000 Real / 10,000 Fake)
- **Image Resolution:** 32 x 32 RGB

## 🛠️ Project Structure
```text
Real vs AI/
│
├── notebook/
│   └── model_training.ipynb     # PyTorch training & architecture notebook
├── train/                        # Local dataset (Excluded from Git)
│   ├── FAKE/
│   └── REAL/
├── test/                         # Local dataset (Excluded from Git)
│   ├── FAKE/
│   └── REAL/
├── .gitignore
└── README.md
