# AI TEXT-TO-IMAGE GENERATOR  
## IBM INTERNSHIP PROJECT

An interactive, high-performance **Text-to-Image Generator** built during an IBM internship. This project converts natural language prompts into AI-generated images using multiple diffusion models. Fully hosted in **Google Colab**, featuring a custom-designed Gradio interface with animations, model switching, and rich UI styling.

---

### LIVE DEMO

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Yozora13/Text-To-Image-Genrator-IBM/blob/main/Text-To-Image-Generator.ipynb)

---

### FEATURES

- Supports model switching (SDXL 1.0, SD 1.5, SDXL Turbo)  
- Random prompt suggestions on reload  
- Adjustable guidance scale, inference steps, and seed  
- Generation history with image gallery  
- Particle burst effect on image generation  
- Styled UI with glassmorphism, gradient buttons, and sliders  
- Download button for generated images  
- Clear history functionality  
- Fully runs in Google Colab — no setup required

---

### SUPPORTED MODELS

- **SDXL 1.0** – High-quality, detailed generation  
- **SD 1.5** – Balanced speed and quality  
- **SDXL Turbo** – Very fast generation with lower quality  

All models are downloaded and cached dynamically.

---

### TECHNOLOGIES USED

- **UI**: Gradio, custom CSS, JavaScript, HTML Canvas  
- **Backend**: Hugging Face Diffusers, PyTorch, PIL  
- **Environment**: Google Colab with GPU runtime  
- **Styling**: Tailwind-inspired layout, glassmorphic cards, glowing buttons and sliders

---

### UI PREVIEW

> *(Add screenshots here to visually showcase the interface and outputs)*

---

### PROJECT STRUCTURE

Text-To-Image-Genrator-IBM/
├── app/
│ ├── main.py # Gradio routing + setup
│ ├── model_handler.py # Model loading and switching
│ └── utils.py # Utilities for memory & image management
├── frontend/ # Inline HTML/CSS/JS via Gradio Blocks
├── public/ # Saved generated image history
├── Text-To-Image-Generator.ipynb # Main Colab notebook
└── README.md
---

---

### HOW TO RUN

1. Open the Colab notebook from the link above  
2. Click "Runtime > Run all"  
3. Wait for the Gradio UI to appear  
4. Enter a prompt or use the random suggestion  
5. Adjust generation settings (optional)  
6. Click "Generate Image"  
7. Download or view your output in the history section  

---

### PROMPT EXAMPLES

- futuristic cyberpunk city at night  
- anime girl under cherry blossom trees  
- a cozy cabin in snowy forest  
- mecha robot in a battle scene  
- surreal dreamscape with melting clocks  

---

### ACKNOWLEDGMENT

This project was created as part of an internship at **IBM**, showcasing a full-stack AI deployment in Colab using Gradio, Hugging Face models, and an interactive modern UI.
