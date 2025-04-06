# NVIDIA_GPU-for-Deep-Learning
A step-by-step guide to setting up and running an NVIDIA GPU on our system — includes Driver installation, CUDA setup, and Testing for deep learning and compute workloads.

# 🔧 NVIDIA GPU Setup Guide : 

This repository provides a comprehensive guide on how to install and configure an NVIDIA GPU on your system — from installing the drivers to setting up CUDA, cuDNN, and testing your setup with a simple deep learning example.

---

## 🖥️ System Requirements

- NVIDIA GPU (Maxwell architecture or newer recommended)
- Windows / Linux
- At least 8 GB RAM (16+ recommended for deep learning)
- Sufficient power supply and compatible motherboard (for desktops)

---

## ✅ Driver Installation

1. Go to the [NVIDIA Driver Downloads](https://www.nvidia.com/Download/index.aspx).
2. Select your GPU model and OS.
3. Download and install the driver.
4. Restart your system.

🛠 To verify driver:
```bash
nvidia-smi
