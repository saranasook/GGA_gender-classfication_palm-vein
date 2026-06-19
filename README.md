# GGA_plam_gender-classfication_plam-vein

# Global Gated Attention (GGA) for Robust Gender Classification in Palm Vein Biometrics

This repository contains the official PyTorch implementation for our framework **GGA-CNN**, which introduces a **Global Gated Attention (GGA)** module at the terminal bottleneck of deep networks to mitigate demographic bias and accurately classify gender from Near-Infrared (NIR) palm vein images.

---

## 📌 Repository Structure

```text
├── gender_model.py          # Model architectures (DenseNet161_GGA_Binary, etc.)
├── gender_train.py                 # Core training loop and evaluation scripts
├── gender_inference.py             # Single-image inference pipeline script
├── requirements.txt         # Required Python dependencies
└── README.md                # Project documentation


🛠️ Installation
1. Clone the Repository
git clone [https://github.com/your-username/palmvein-gga-gender.git](https://github.com/your-username/palmvein-gga-gender.git)
cd palmvein-gga-gender
