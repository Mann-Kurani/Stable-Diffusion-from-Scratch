
# **Stable Diffusion Inference from Scratch** 🚀  

This project reconstructs the **Stable Diffusion inference pipeline from scratch**, implementing **UNet, VAEs, and DDPM sampling** for image generation. While model weights are imported (no training loops included), the architecture is built entirely from the ground up.  

---

## **🖼️ Overview**  
Stable Diffusion is a **latent diffusion model** that generates high-quality images from text or existing images. This project focuses on:  
- **DDPM (Denoising Diffusion Probabilistic Models)** for image generation  
- **UNet** for noise prediction  
- **VAE** for encoding and decoding latent representations  
- **Text-to-Image & Image-to-Image generation**  

Tested on **cute cow images** 🐮—the results were surprisingly good! 😆  

---

## **✨ Features**  
✅ **Stable Diffusion inference pipeline** built from scratch  
✅ **Text-to-Image & Image-to-Image generation**  
✅ **DDPM-based sampling process**  
✅ **Custom UNet implementation**  
✅ **Configurable inference settings**  
✅ **Demo notebook included!**  

---


### **🔹 Clone the Repository**  
```bash
git clone https://github.com/yourusername/stable-diffusion-inference.git
cd stable-diffusion-inference
```

---


## **🖥️ Running the Demo**  
To quickly test the model, run the **demo notebook**:  

```bash
jupyter notebook demo.ipynb
```
Follow the provided steps to generate images interactively.  

---

## **📝 Project Structure**  
```
📂 stable-diffusion-inference
 ┣ 📜 ddpm.py       # Implements DDPM Sampler  
 ┣ 📜 diffusion.py  # UNet, VAEs, and model components  
 ┣ 📜 pipeline.py   # Complete image generation pipeline  
 ┣ 📜 demo.ipynb    # Jupyter Notebook for interactive demo  
 ┗ 📜 README.md     # Project documentation  
```

---

## **🙌 Acknowledgments**  
🔹 Inspired by **Umar Jamil’s YouTube tutorials**  
🔹 Research papers on **Diffusion Models & VAEs**  

---

## **📜 License**  
This project is open-source under the **MIT License**.  

