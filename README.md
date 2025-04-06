# NVIDIA_GPU-for-Deep-Learning
A step-by-step guide to setting up and running an NVIDIA GPU on our system — includes Driver installation, CUDA setup, and Testing for deep learning and compute workloads.

# 🔧 NVIDIA GPU Setup Guide : 

This repository provides a comprehensive guide on how to install and configure an NVIDIA GPU on your system — from installing the drivers to setting up CUDA, cuDNN, and testing your setup with a simple deep learning example.

---

## ✅ Step-by-Step Procedure :

### STEP 01 : NVIDIA Driver  

We should install the latest version of our GPU's driver. It can be downloaded from:   
- [NVIDIA GPU Driver Download](https://www.nvidia.com/en-us/drivers/)

### STEP 02 : Visual Studio C++

We need Visual Studio, with C++ installed. By default, C++ is not available with Visual Studio, so make sure to select all C++ options.  
- [Visual Studio 2022 Community Edition](https://visualstudio.microsoft.com/vs/community/)

### STEP 03 : Anaconda/ Miniconda

We will need Ananconda or Miniconda to install deep learning packages.  
- [Anaconda Download Site](https://www.anaconda.com/download)

### STEP 04 : CUDA Toolkit

We also need to install CUDA-Toolkit.  
- [Download CUDA Toolkit ](https://developer.nvidia.com/cuda-toolkit-archive)

### STEP 05 : cuDNN

We also need to install cuDNN.  
- [Download cuDNN](https://developer.nvidia.com/rdp/cudnn-archive)

### STEP 06 : Install PyTorch
We need to install PyTorch-Cuda supported. 
- [Install PyTorch](https://pytorch.org/get-started/locally/)

### Finally run the following script to test your GPU
```bash
import torch

print("Number of GPU :",torch.cuda.device_count())
print("GPU Name :",torch.cuda.get_device_name())

device = torch.device('cuda' if torch.cuda.is_available() else 'cpu')
print("Using Device",device)
```
--- 
### 🖥️ For Reference Youtube Video : 
- [How to Setup NVIDIA GPU for Deep Learning](https://youtu.be/nATRPPZ5dGE?feature=shared)
