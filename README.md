# NVIDIA_GPU-for-Deep-Learning
A step-by-step guide to setting up and running an NVIDIA GPU on our system — includes Driver installation, CUDA setup, and Testing for deep learning and compute workloads.

# 🔧 NVIDIA GPU Setup Guide : 

This repository provides a comprehensive guide on how to install and configure an NVIDIA GPU on your system — from installing the drivers to setting up CUDA, cuDNN, and testing your setup with a simple deep learning example.

---

## 🖥️ Step-by-Step Procedure :

### STEP 01 : NVIDIA Driver  

We should install the latest version of our GPU's driver. It can be downloaded from:   
- [NVIDIA GPU Driver Download](https://www.nvidia.com/en-us/drivers/).

### STEP 02 : Visual Studio C++

We need Visual Studio, with C++ installed. By default, C++ is not available with Visual Studio, so make sure to select all C++ options.  
- [Visual Studio 2022 Community Edition](https://visualstudio.microsoft.com/vs/community/).

### STEP 03 : Visual Studio C++

We need Visual Studio, with C++ installed. By default, C++ is not available with Visual Studio, so make sure to select all C++ options.  
- [Visual Studio 2022 Community Edition](https://visualstudio.microsoft.com/vs/community/).

---

## ✅ Driver Installation

1. Go to the [NVIDIA Driver Downloads](https://www.nvidia.com/Download/index.aspx).
2. Select your GPU model and OS.
3. Download and install the driver.
4. Restart your system.

🛠 To verify driver:
```bash
nvidia-smi
