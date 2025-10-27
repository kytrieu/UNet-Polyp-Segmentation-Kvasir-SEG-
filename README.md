# UNet-Polyp-Segmentation-Kvasir-SEG-


# 🩺 Polyp Segmentation using U-Net (Kvasir-SEG)

This project implements a **U-Net** model for polyp segmentation in colonoscopy images using the **Kvasir-SEG** dataset.

## 📂 Dataset
- **Dataset:** [[Kvasir-SEG](https://datasets.simula.no/kvasir-seg/)](https://www.kaggle.com/datasets/debeshjha1/kvasirseg)
- Contains 1000 annotated images and corresponding masks.
- Each image has a segmentation mask highlighting the polyp region.

## 🧱 Model Architecture
- Based on **U-Net**, a convolutional neural network designed for biomedical image segmentation.
- Encoder: Convolution + MaxPooling layers.
- Decoder: Transposed Convolutions + Skip connections.
- Output: Sigmoid activation for binary segmentation.


