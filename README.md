# Image-to-Image Translation using Pix2Pix (cGAN)

## 📌 Overview

This project was developed as part of **Task 04** of the **Prodigy Infotech Generative AI Internship**. The objective is to implement an image-to-image translation model using a **Conditional Generative Adversarial Network (cGAN)** called **Pix2Pix**.

Instead of training the model from scratch, the official pre-trained Pix2Pix implementation was used to perform image translation on the Facades dataset. The model successfully converted semantic building label images into realistic building photographs.

---

## 🎯 Objectives

- Implement image-to-image translation using Pix2Pix.
- Use a pre-trained Conditional GAN (cGAN).
- Translate semantic label maps into realistic building images.
- Understand the working of Generator and Discriminator networks.

---

## 🛠️ Technologies Used

- Python
- Google Colab
- PyTorch
- torchvision
- Pillow (PIL)
- Matplotlib
- Pix2Pix (cGAN)

---

## 📂 Project Structure

```
Task_04_Image_to_Image_Translation/
│
├── PRODIGY_GA_04_Image_to_Image_Translation.ipynb
├── README.md
├── requirements.txt
├── Task04_Report.pdf
└── generated_results/
```

---

## 🚀 Workflow

1. Install required libraries.
2. Clone the official Pix2Pix repository.
3. Download the pre-trained Pix2Pix model.
4. Download the Facades dataset.
5. Perform image-to-image translation.
6. Visualize the generated images.

---

## 📈 Results

The Pix2Pix model successfully translated semantic building labels into realistic building photographs using the pre-trained Generator network. The generated outputs preserved the structural information from the input images while producing visually realistic results.

---

## 📚 Learning Outcomes

- Understanding Conditional GANs (cGANs)
- Working with the Pix2Pix architecture
- Performing inference using pre-trained deep learning models
- Image-to-image translation concepts
- Practical experience with Generative AI and Computer Vision

---

## 🙏 Acknowledgement

This project was completed as part of the **Prodigy Infotech Generative AI Internship**.