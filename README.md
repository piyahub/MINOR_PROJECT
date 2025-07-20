
# 🧠✨ Image Augmentation Using GANs (DCGAN based)  

## 📌 Overview

This project uses a **Deep Convolutional GAN (DCGAN)** to generate synthetic images for **image augmentation**, especially useful for handling class imbalance and enriching datasets.  

✅ Built & trained entirely on **Google Colab** with GPU support.  
✅ Uses **PyTorch** for model development.  
✅ Outputs high-quality fake images using adversarial training.

---

## 🚀 Demo Notebook

🔗 [Click here to open the notebook in Google Colab](https://colab.research.google.com/drive/15leUZj0DC8-Tr6ByaD1_cnU6UTmoel-p?usp=sharing)

---

## 🔧 Tech Stack & Tools

| Tool              | Usage                            |
|-------------------|----------------------------------|
| 🐍 Python         | Core programming language         |
| 🔥 PyTorch        | Deep learning framework           |
| 🧪 Torchvision     | Image preprocessing               |
| 📊 Matplotlib     | Visualizing training and outputs  |
| 💻 Google Colab   | Training & running the notebook   |
| 💾 CUDA/GPU       | Accelerated model training        |

---

## 🧠 Model Architecture

- **Generator**: Transforms random noise into realistic images using transposed convolution layers, batch normalization, and ReLU activations.
- **Discriminator**: Classifies real vs. fake images using convolution layers and LeakyReLU.
- **Loss Function**: Binary Cross Entropy Loss (BCE)
- **Optimizer**: Adam (learning rate = 0.0002, betas = (0.5, 0.999))

---

## 🖼️ Sample Outputs


![Screenshot 2025-04-21 224647](https://github.com/user-attachments/assets/954da17a-286a-46f7-842e-f5eb69ec885a)



![Screenshot 2025-04-21 225657](https://github.com/user-attachments/assets/3fd0ffaf-0c95-42b3-a28c-d9bd55d829d8)

