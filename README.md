# 🌀 **Diffusion Models from Scratch with PyTorch**

This project is a step-by-step implementation of a Denoising Diffusion Probabilistic Model (DDPM) using PyTorch. It walks through the full training pipeline from data loading and noise scheduling to building a simplified U-Net, training the model, and generating new images from pure noise.

📖 **Features**:
* 🚀 Uses CUDA for fast GPU-accelerated training
* 🖼️ Trains on the CIFAR-10 image dataset
* 🔁 Implements forward and reverse diffusion processes
* 🧠 Builds and trains a simple U-Net to denoise images
* 🎨 Generates new images by reversing the diffusion steps
* 👁️ Visualizes intermediate denoising steps

🛠️ Setup
1. **Install dependencies**:
   <pre><code>pip install torch torchvision torchaudio matplotlib numpy </code></pre>

2. **Run the notebook**:<br><br>
   You can open and execute the notebook in Jupyter or any environment like Google Colab.


📚 **Learning Outcomes**
* Understand the theory and math behind DDPMs
* Learn how noise scheduling works in diffusion models
* Implement a neural network to reverse noise in images
* Generate novel samples from random noise using deep learning

📎 **References**<br><br>
See the **References** section in the notebook for key papers and resources.
