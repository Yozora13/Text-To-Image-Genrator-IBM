# AI TEXT-TO-IMAGE GENERATOR  
## IBM INTERNSHIP PROJECT

An interactive, high-performance **Text-to-Image Generator** built during an IBM internship. This project converts natural language prompts into AI-generated images using multiple diffusion models. Fully hosted in **Google Colab**, featuring a custom-designed Gradio interface with animations, model switching, and rich UI styling.

---

### LIVE DEMO

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Yozora13/Text-To-Image-Genrator-IBM/blob/main/Text_to_image_genrator.ipynb)

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

> <img width="1457" height="858" alt="Screenshot 2025-07-27 090331" src="https://github.com/user-attachments/assets/1bf07e79-4ff9-4975-b95a-15be71e1603b" />
<img width="1023" height="1077" alt="Screenshot 2025-07-27 091314" src="https://github.com/user-attachments/assets/693c8357-6af2-4ee0-b204-537ca7a437af" />

---

### PROJECT STRUCTURE
<pre>
Text-To-Image-Genrator-IBM/
↳ app/
  ↳ main.py               # Gradio routing + setup
  ↳ model_handler.py      # Model loading and switching logic
  ↳ utils.py              # Utilities for memory & image management
↳ frontend/               # Inline HTML/CSS/JS for custom UI (via Gradio Blocks)
↳ public/                 # Stores saved/generated image history
↳ Text-To-Image-Generator.ipynb  # Main Google Colab notebook
↳ README.md              # Project overview
</pre>
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
