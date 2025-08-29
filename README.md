# 🎨 Conditional GAN for Image Generation

Welcome to the official repository for a **Conditional Generative Adversarial Network (CGAN)** project focused on class-conditional image generation and evaluation using FID score.
[Open in Colab](https://colab.research.google.com/drive/15leUZj0DC8-Tr6ByaD1_cnU6UTmoel-p?usp=sharing)

---

## 🧠 What is a CGAN?

A Conditional GAN is a type of Generative Adversarial Network where both the generator and discriminator are conditioned on auxiliary information (like class labels). This allows for targeted image generation — e.g., generating a specific digit/class.

---

## 📌 Features

- ✅ Conditional image generation using CGAN
- 🧪 Trained on image dataset (e.g., MNIST / Custom)
- 🧠 Uses **VGG16** for feature extraction
- 📊 Calculates **FID (Fréchet Inception Distance)** for image quality
- 💾 Saves generated images and models
- 📉 Tracks training progress visually

---

## 🛠️ Tech Stack

- **Python**
- **PyTorch**
- **NumPy, Matplotlib**
- **PIL (Pillow)**
- **VGG16 (torchvision)**
- **Jupyter Notebook**

---

## 📁 Files

| File | Description |
|------|-------------|
| `FinalCgan.ipynb` | Main notebook containing full CGAN implementation |
| `generated_images/` | Folder where generated images are saved |
| `saved_models/` | Folder containing generator & discriminator weights |

---


## 📈 FID Score Calculation

FID is used to measure the similarity between real and generated images using VGG features.

Lower FID = More realistic images ✅

---

