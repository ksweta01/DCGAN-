# 🎨 DCGAN for AI-Generated Art

This project demonstrates how to build and train a **Deep Convolutional Generative Adversarial Network (DCGAN)** to generate synthetic art images. Using a collection of real art images as training data, the model learns to generate realistic-looking artistic visuals, making it a powerful tool for creative AI applications.

---

## 🧠 What is DCGAN?

A **DCGAN (Deep Convolutional GAN)** is a type of Generative Adversarial Network that uses deep convolutional layers in both the generator and discriminator. It is well-suited for generating images due to its ability to capture spatial hierarchies and patterns.


## 🗂️ Project Structure

## 🖼️ Dataset

- **Source:** A custom or public dataset of art images (abstract, modern, etc.)
- **Format:** `.jpg` or `.png` images resized to 64x64 pixels
- **Size:** Recommended: At least 2,000–5,000 images for stable training

> Unzip `Images.zip` and place the folder where the notebook can access it.

---

## 🧪 How It Works

1. **Generator:** Takes a random noise vector (latent space) and generates an image.
2. **Discriminator:** Takes real or fake images and classifies them as real or generated.
3. **Training:** 
   - The generator learns to fool the discriminator.
   - The discriminator learns to distinguish between real and generated images.
4. **Output:** Over time, the generator produces increasingly realistic art.



## ⚙️ Libraries Used

- Python (3.x)
- PyTorch
- NumPy
- Matplotlib
- torchvision


## 🚀 How to Run

1. Clone the repo or download the notebook and dataset
2. Install dependencies (preferably in a virtual environment)
   ```bash
   pip install torch torchvision matplotlib numpy
