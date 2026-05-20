# 🖼️ MNIST & CIFAR-100 Dataset Exploration using PyTorch

> Hands-on exploration of two benchmark image datasets — MNIST and CIFAR-100 — using PyTorch and TorchVision. Covers dataset loading, train/test splitting, and visual analysis of image samples with class labels.

![Python](https://img.shields.io/badge/Python-3.12-blue?logo=python)
![PyTorch](https://img.shields.io/badge/PyTorch-2.0-red?logo=pytorch)
![TorchVision](https://img.shields.io/badge/TorchVision-0.15-orange)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter)

---

## Overview

This project provides a structured exploration of two widely used computer vision datasets:

- **MNIST** — 70,000 grayscale images of handwritten digits (0–9), 28×28 pixels
- **CIFAR-100** — 60,000 color images across 100 fine-grained classes, 32×32 pixels

The notebook demonstrates how to load, split, and visualize these datasets as a foundation for building image classification models with deep learning.

---

## Datasets

| Dataset | Classes | Images | Size | Type |
|---------|---------|--------|------|------|
| MNIST | 10 | 70,000 | 28×28 | Grayscale |
| CIFAR-100 | 100 | 60,000 | 32×32 | RGB Color |

---

## What's Covered

- Loading MNIST and CIFAR-100 via `torchvision.datasets`
- Applying transforms — normalization and tensor conversion
- 80/20 train/test split using `torch.utils.data.random_split`
- Visualizing sample images with their class labels using Matplotlib
- Exploring dataset structure — shapes, class distributions, and pixel statistics

---

## Tech Stack

| Tool | Purpose |
|------|---------|
| PyTorch | Deep learning framework |
| TorchVision | Dataset loading and transforms |
| Matplotlib | Image visualization |
| NumPy | Array operations |
| Jupyter Notebook | Interactive exploration |

---

## Getting Started

### Prerequisites
- Python 3.8+
- PyTorch 2.0+

### Installation

```bash
git clone https://github.com/prasadnikita/MNIST-CIFAR-100-Dataset-Exploration-using-PyTorch.git
cd MNIST-CIFAR-100-Dataset-Exploration-using-PyTorch
pip install torch torchvision matplotlib numpy jupyter
```

### Run

```bash
jupyter notebook ACV_Project1.ipynb
```

> Datasets download automatically on first run via TorchVision.

---

## Project Structure

```
MNIST-CIFAR-100-Dataset-Exploration-using-PyTorch/
├── ACV_Project1.ipynb    # Main exploration notebook
└── README.md
```

---

## License

MIT
