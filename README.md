# 🎨 AI Text-to-Image Generator with Stable Diffusion

A simple yet powerful application that generates images from text prompts using the Stable Diffusion model. This entire project is self-contained within a Google Colab notebook and features a modern, interactive user interface built with Gradio.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1aHhruYErvy852gl8rH51F1jnEJwU3UxA)

---

## ✨ Features

* **High-Quality Image Generation:** Leverages the `runwayml/stable-diffusion-v1-5` model to create detailed images from text descriptions.
* **Interactive Web UI:** A user-friendly interface built with Gradio allows for easy interaction without needing to modify any code.
* **Self-Contained Notebook:** The entire application, from model loading to the UI, runs within a single Google Colab file.
* **GPU Accelerated:** Utilizes the free T4 GPU provided by Google Colab for fast image generation.
* **Modern Design:** Features a clean, full-screen layout with themes, example prompts, and branding.

---

## 📸 Screenshot

![alt text](https://github.com/Shubham-py404/Text-To-Image/edit/main/image.jpg?raw=true)



## 🛠️ Technologies Used

This project is built with a stack of powerful, open-source AI and web technologies:

* **Python:** The core programming language.
* **Google Colab:** For the interactive notebook environment and free GPU access.
* **PyTorch:** The deep learning framework that powers the AI model.
* **Hugging Face `diffusers`:** The toolkit used to easily download and run the Stable Diffusion pipeline.
* **Hugging Face `transformers`:** Used to convert text prompts into a format the model can understand (embeddings).
* **Gradio:** The library used to rapidly create the polished and interactive web UI.
* **Safetensors:** A modern, secure, and fast file format for storing the AI model's weights.

---

## 🚀 Getting Started

To run this project yourself, follow these simple steps:

1.  **Open in Google Colab:**
    Click the "Open in Colab" badge at the top of this README or open the `text_to_image.ipynb` file directly in Google Colab.

2.  **Set the Runtime to GPU:**
    Before running anything, ensure your hardware accelerator is set to GPU.
    * In the menu, go to `Runtime` > `Change runtime type`.
    * Select **`T4 GPU`** from the dropdown menu and click `Save`.

3.  **Run the Cells:**
    Run each code cell in the notebook in order, from top to bottom. The notebook will install all necessary libraries, load the model, and define the functions.

4.  **Launch the UI:**
    The final cell will launch the Gradio application. It will automatically open in a new, full-screen browser tab for the best experience. Now you can start creating images!
