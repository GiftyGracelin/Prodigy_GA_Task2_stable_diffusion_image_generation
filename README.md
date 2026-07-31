# Image Generation using Stable Diffusion

## Prodigy InfoTech – Generative AI Internship

### Task-02: Image Generation with Pre-trained Models

---

## 📌 Project Overview

This project demonstrates how to generate images from text prompts using the pre-trained **Stable Diffusion** model. The implementation is developed in **Google Colab** using the **Hugging Face Diffusers** library and **PyTorch**.

The notebook generates realistic AI images from user-defined text prompts and automatically saves them for future use.

---

## 🎯 Objective

To utilize a pre-trained generative AI model (Stable Diffusion) to create images from natural language text prompts.

---

## 🛠️ Technologies Used

- Python
- Google Colab
- PyTorch
- Hugging Face Diffusers
- Transformers
- Accelerate
- Safetensors
- Pillow
- Matplotlib

---

## 📂 Project Structure

```
PRODIGY_GA_02/
│
├── Stable_Diffusion.ipynb
├── README.md
├── requirements.txt
└── outputs/
    ├── astronaut_horse.png
    ├── futuristic_city.png
    ├── fantasy_castle.png
    ├── robot.png
    └── baby_dragon.png
```

---

## 📦 Installation

Install the required libraries before running the notebook.

```bash
pip install diffusers transformers accelerate safetensors torch pillow matplotlib
```

---

## ▶️ How to Run

1. Open **Task_02_Stable_Diffusion.ipynb** in **Google Colab**.
2. Enable **GPU** by navigating to:
   - **Runtime → Change runtime type → T4 GPU** (or any available GPU).
3. Run each notebook cell in order.
4. Wait for the Stable Diffusion model to download (only required the first time).
5. Enter or modify the text prompts as desired.
6. Generated images will be displayed and saved automatically in the **outputs** folder.

---

## 💡 Sample Prompts

- An astronaut riding a horse on the moon
- A futuristic city at sunset
- A fantasy castle on floating islands
- A robot painting a landscape
- A cute baby dragon reading books

---

## 📁 Output

The notebook automatically saves the generated images in the **outputs/** directory.

Example outputs:

- astronaut_horse.png
- futuristic_city.png
- fantasy_castle.png
- robot.png
- baby_dragon.png

---

## ✨ Features

- Generates high-quality images from text prompts
- Uses a pre-trained Stable Diffusion model
- GPU-accelerated image generation
- Supports multiple prompts
- Automatically saves generated images
- Displays generated images within the notebook

---

## 📚 References

1. TensorFlow – Stable Diffusion Tutorial  
   https://www.tensorflow.org/tutorials/generative/generate_images_with_stable_diffusion

2. DALL·E Mini Google Colab Notebook  
   https://colab.research.google.com/github/robgon-art/e-dall-e/blob/main/DALL_E_Mini_Image_Generator.ipynb

3. Towards Data Science – DALL·E Mini  
   https://towardsdatascience.com/e-dall-e-creating-digital-art-with-varying-aspect-ratios-5de260f4713d/

4. Diffusion-Colab GitHub Repository  
   https://github.com/faizonly5953/Diffusion-Colab

---

## 👩‍💻 Author

**Gifty Gracelin I**

Generative AI Intern – Prodigy InfoTech
