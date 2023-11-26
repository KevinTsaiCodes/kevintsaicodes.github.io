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

What is _virtual environment_ in Python? A Python virtual environment, often abbreviated as `venv`, is a self-contained directory that contains a Python interpreter along with standard libraries and other supporting files. The purpose of creating a virtual environment is to isolate Python projects and their dependencies. This helps to avoid conflicts between different projects that may require different versions of libraries or dependencies.

**Create Virtual Environment**

1. Open Anaconda Prompt
2. Type `conda create --name venv-name python=edition` for _virtual environment_ creation. For example, if I want to create a virtual environment named `myenv` with Python `version 3.5`, I would need to type (in the Anaconda Prompt):
   
   `conda create --name myenv python=3.5`

**Activate/Deactivate Virtual Environment**

`conda activate venv-name` (for _virtual environment_ activate)

`conda deactivate venv-name` (for _virtual environment_ deactivate)
