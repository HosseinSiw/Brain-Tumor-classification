# 🧠 Brain Tumor Classification with EfficientNet

This project uses deep learning with PyTorch and EfficientNet to classify MRI brain scans into **tumor** and **non-tumor** classes. It is a binary image classification problem designed to assist in medical diagnosis using automated systems.

## 🧬 Model Architecture

- 🔥 **EfficientNet** – Lightweight and high-performing CNN architecture
- ⚡ Mixed Precision Training using `torch.cuda.amp`
- 🧪 Evaluation using Accuracy and F1-score from `torchmetrics`

## 🗂️ Dataset
The dataset is from [Kaggle](https://www.kaggle.com/datasets/navoneel/brain-mri-images-for-brain-tumor-detection) 
The dataset is assumed to be organized in an `ImageFolder` format:


```
dataset/
├── tumor/
│   ├── image1.jpg
│   ├── ...
├── no_tumor/
│   ├── image1.jpg
│   ├── ...
```

You can adjust the paths in the notebook to fit your dataset structure.

## 🚀 Training Configuration

- Batch Size: 32
- Epochs: 35
- Device: GPU (if available)
- Evaluation Metrics:
  - Accuracy
  - F1-score

## 📦 Dependencies

Install all the required libraries with:

```bash
pip install torch torchvision torchmetrics efficientnet_pytorch tqdm matplotlib scikit-learn
```

## 🧪 How to Run

1. Place your dataset in the required structure.
2. Update dataset path in the notebook.
3. Run the notebook: `brain-tumor-classification.ipynb`.

## 📊 Output

- Model training history plots
- Final metrics: Accuracy and F1
- Torch AMP-based training for performance boost

## 💡 Highlights

- Efficient and lightweight model for medical imaging
- GPU-accelerated mixed precision training
- Modular and easy to understand PyTorch code

---

### Author

Made with 🧠 and ❤️ by [Your Name]
