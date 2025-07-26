# 🧠 Brain Tumor Segmentation using MedSAM-2 on BraTS20 Dataset

This project evaluates the performance of the **MedSAM-2** model for brain tumor segmentation using the **BraTS 2020** dataset. The segmentation task focuses on identifying tumor sub-regions such as necrotic core, edema, and enhancing tumor using pretrained medical SAM models.

---

## 📌 Task Overview

**Task 02**: Inference and Evaluation of MedSAM-2 on Brain Tumor Segmentation (BraTS 2020)

- **Dataset**: [BraTS 2020 - Training & Validation](https://www.kaggle.com/datasets/awsaf49/brats20-dataset-training-validation)
- **Model**: [`MedSAM-2`](https://huggingface.co/wanglab/MedSAM2)
- **Framework**: PyTorch
- **Environment**: Kaggle Kernel
- **Hardware**: Tesla T4 GPU (Kaggle Runtime)

---

## 🧪 Objectives

- Load and preprocess multimodal MRI scans from BraTS.
- Visualize MRI modalities and segmentation ground truths.
- Load pretrained MedSAM-2 model checkpoints.
- Run inference on a selected BraTS sample.
- Visualize and evaluate predicted masks vs ground truths.
- Fix compatibility issues related to model inference in Kaggle.

---

## 🔧 Dependencies

Install required libraries:

```bash
pip install nibabel
pip install opencv-python
pip install matplotlib
pip install -U torch torchvision torchaudio

