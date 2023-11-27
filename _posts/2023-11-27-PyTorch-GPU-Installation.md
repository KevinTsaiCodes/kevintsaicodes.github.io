---
title: "PyTorch Installation (with CUDA)"
tags:
  - PyTorch
  - CUDA
---

**Getting Started**

Before installation, you need to download the dependencies required by PyTorch (with CUDA).

1. [Anaconda](https://www.anaconda.com/)
2. [PyCharm](https://www.jetbrains.com/pycharm/)

After downloading and completing the installation of Anaconda and PyCharm, I will now guide you through the installation of PyTorch with CUDA.

**Virtual Environment**

What is _virtual environment_ in Python? A Python _virtual environment_, often abbreviated as `venv`, is a self-contained directory that contains a Python interpreter along with standard libraries and other supporting files. The **purpose** of creating a virtual environment is to **isolate Python projects and their dependencies**. This **helps to avoid conflicts between different projects that may require different versions of libraries or dependencies**.

**Create Virtual Environment**

1. Open Anaconda Prompt
2. Type `conda create --name venv-name python=edition` for _virtual environment_ creation. For example, if I want to create a virtual environment named `myenv` with Python `version 3.5`, I would need to type (in the Anaconda Prompt):
   
   `conda create --name myenv python=3.5`

**Activate/Deactivate Virtual Environment**

`conda activate venv-name` (**activate** _virtual environment_)

`conda deactivate venv-name` (**deactivate** _virtual environment_)

**PyTorch (with CUDA) Installation**

After activating your self-defined virtual environment in the Anaconda command prompt, the installation command for PyTorch (with CUDA) is as follows:

    pip3 install torch torchvision torchtext torchaudio --index-url https://download.pytorch.org/whl/cu118

⚠️**Need to be noticed!**

**Cheat Sheet of PyTorch**: [Link](https://hackmd.io/@rh0jTfFDTO6SteMDq91tgg/HkDRHKLrU)
