# 🩺 Skin Cancer Detection using Machine Learning and Quantum Computing

A hierarchical deep learning system combining ResNet50 architecture with quantum computing for skin cancer classification.

## 🚀 Demo

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Hamsa786/resnet50-quantum-skin-cancer/blob/main/Final_ResNet50_Demo.ipynb)

> Open the notebook in Colab, run all cells, and the Gradio demo will launch automatically. No setup needed!

## 🖼️ Sample Images for Testing

Sample test images are available in the [`Sample Images For Testing`](./Sample%20Images%20For%20Testing/) folder — 3 images from each of the 7 lesion types (21 images total).

Simply download any image and upload it to the Gradio demo to test!

## 🏆 Model Performance

| Model | Binary Accuracy | 7-Class Accuracy |
|-------|----------------|-----------------|
| Classical ResNet50 | 88.9% | 78.9% |
| Quantum ResNet50 | 90.4% | 80.6% |

> 🎯 Quantum model wins by 1.7%!

## 🔬 Architecture

- **Backbone:** ResNet50 (50-layer deep CNN)
- **Quantum Layer:** 8-qubit quantum circuit (PennyLane)
- **Approach:** Hierarchical classification — Binary (Malignant/Benign) → 7-class lesion type
- **Dataset:** HAM10000 (3,500 balanced training images, 7 lesion types)

## 🧬 Lesion Types Detected

| Class | Type | Category |
|-------|------|----------|
| MEL | Melanoma | Malignant |
| BCC | Basal Cell Carcinoma | Malignant |
| AKIEC | Actinic Keratosis | Malignant |
| NV | Melanocytic Nevi | Benign |
| BKL | Benign Keratosis | Benign |
| DF | Dermatofibroma | Benign |
| VASC | Vascular Lesions | Benign |

## 📁 Repository Structure
```
├── Final_ResNet50_Demo.ipynb          # ⭐ Run this for demo
├── ResNet50_Quantum_Hybrid_Final.ipynb # Full training notebook
└── README.md
```

## 🛠️ Tech Stack

- Python, PyTorch, PennyLane
- ResNet50, Quantum Computing
- Gradio, scikit-learn
- HAM10000 Dataset

## 📌 Model Weights

Pretrained models hosted on Hugging Face:
[Hamsa745/resnet50-quantum-skin-cancer](https://huggingface.co/Hamsa745/resnet50-quantum-skin-cancer)
