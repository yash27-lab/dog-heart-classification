# 🐶 Dog Heart Classification - ViT Model (LFS Powered)

This repository contains the best-performing Vision Transformer (ViT) model trained for classifying dog heart X-ray images.

## 📦 Files

| File                        | Description                              |
|----------------------------|------------------------------------------|
| `dog_heart_vit_best.pth`   | ViT model weights (343 MB, LFS-tracked)  |
| `.gitattributes`           | Git LFS tracking config                   |

> ✅ This repo uses [Git LFS](https://git-lfs.github.com/) to manage large files

## 🧠 Usage

```python
import torch
model = torch.load('dog_heart_vit_best.pth', map_location=torch.device('cpu'))
model.eval()
# Now use model for inference...
