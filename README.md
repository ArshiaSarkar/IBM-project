# 👗 Smart AI Stylist – Fashion from Your Photo 👥

A Generative AI project that recommends and *generates* realistic outfits based on your **uploaded full-body image** and a chosen **occasion**. Built using Segment Anything + Stable Diffusion Inpainting + Gradio UI.

---

## 🔗 Colab Notebook

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1f6vdnD_fM5TpaK6enLSJzz-6ARTCt3fq?usp=sharing)

---

## 🛠️ Installation (Colab Auto Installs)

If you're using **Google Colab**, dependencies are auto-installed:

```bash
!pip install -q opencv-python matplotlib pillow
!pip install -q git+https://github.com/facebookresearch/segment-anything.git
!pip install -q git+https://github.com/huggingface/diffusers.git
!pip install -q transformers accelerate
!pip install -q gradio
!pip install -q scikit-image
```

Download SAM checkpoint:

```bash
wget https://dl.fbaipublicfiles.com/segment_anything/sam_vit_b_01ec64.pth
```

---

## ✅ Supported Occasions

* `wedding`
* `office party`
* `casual outing`
* `formal event`
* `cocktail`
* `birthday party`
* `business meeting`
* `date night`
* `vacation`
* `festival`

---

## 📚 File Overview

```bash
📆 ai_stylist.ipynb     # Main notebook
📃 README.md             # This file
🐾 sam_vit_b_01ec64.pth  # Segment Anything checkpoint (auto-downloaded)
```

---

## 🧰 Tech Stack

* Meta Segment Anything (SAM)
* HuggingFace Diffusers
* Stable Diffusion Inpainting
* Gradio for UI
* Python + OpenCV + NumPy + PIL

---

## 📸 Demo
![Screenshot 2025-06-23 000813](https://github.com/user-attachments/assets/aa68ce63-bcc9-4994-8703-4f4518cbac72)
---

## 📚 License

MIT License

---

## ✨ Built with ❤️ by Arshia Sarkar
