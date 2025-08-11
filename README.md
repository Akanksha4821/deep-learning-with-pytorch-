#  Deep Learning with PyTorch

Welcome to my PyTorch notebook series — a hands-on learning journey where I explore foundational deep learning concepts using PyTorch. Each notebook includes step-by-step explanations, custom code, and visualizations to reinforce understanding.

>  **Note:** This series follows the [Zero to Mastery: PyTorch for Deep Learning](https://www.learnpytorch.io/) book. The code and explanations are adapted from the course and extended with my own notes, experiments, and interpretations as I learn.  

-----


## 📘 Completed Modules

### `00_pytorch_fundamentals.ipynb`
🔹 Introduction to tensors, datatypes, device setup  
🔹 Tensor operations, reshaping, aggregation  
🔹 Matrix multiplication & broadcasting  
🔹 NumPy interoperability, GPU acceleration  
🔹 Common shape errors explained  
🔹 Exercises included

### `01_pytorch_workflow.ipynb`
🔹 Data loading and preprocessing  
🔹 Building a linear model with `nn.Module`  
🔹 Loss, optimizer setup, training/testing loops  
🔹 Inference and model evaluation  
🔹 Model saving/loading for deployment  

### `02_pytorch_classification.ipynb`
🔹 Binary & multi-class classification with PyTorch  
🔹 Model architecture (`nn.Sequential` and custom)  
🔹 Training loop with `CrossEntropyLoss`, accuracy  
🔹 Softmax, logits, prediction probability  
🔹 Decision boundary visualization  
🔹 Activation functions, metrics  
🔹 Well-commented, beginner-focused examples

### `03_pytorch_computer_vision.ipynb`
🔹 Introduction to computer vision workflows in PyTorch  
🔹 Exploring and visualizing the FashionMNIST dataset  
🔹 Efficient data loading with `DataLoader`  
🔹 Building and training multiple models:
  - Model 0: Baseline Linear Model  
  - Model 1: Model with Non-Linearity  
  - Model 2: CNN-based Classifier  
🔹 Loss/optimizer setup, device-agnostic training (CPU/GPU)  
🔹 Evaluation metrics, prediction visualization, confusion matrix  
🔹 Saving and loading the best performing model

### `04_pytorch_custom_datasets.ipynb`
🔹 Downloading and organizing a custom image dataset (pizza, steak, sushi 🍕🥩🍣)  
🔹 Building a PyTorch-compatible dataset structure from scratch  
🔹 Creating custom `Dataset` class using `torch.utils.data.Dataset`  
🔹 Manual image-path and label mapping  
🔹 Applying image transforms and data augmentation  
🔹 Loading custom dataset with `DataLoader`  
🔹 Building and training a TinyVGG CNN on custom data  
🔹 Diagnosing overfitting/underfitting using train/test loss curves  
🔹 Predicting on custom images with trained models

### '05_pytorch_going_modular.ipynb'
🔹 Converting exploratory notebook cells into clean, reusable .py scripts

🔹 Understanding cell mode vs. script mode and when to use each

🔹 Designing a modular file structure for PyTorch projects:
   data_setup.py → Dataset preparation & DataLoader creation
   model_builder.py → Model architectures
   engine.py → Training & evaluation loops
   utils.py → Saving/loading models, helper functions
   train.py → Script to orchestrate the entire training process
   
🔹 Benefits of modularity: better readability, maintainability, and reproducibility

🔹 Writing scripts that can be run both from CLI and imported into notebooks

🔹 Step-by-step migration of code from 04. PyTorch Custom Datasets into modules

---

## 🗂 Notebook Index

- 📒 [Chapter 0: PyTorch Fundamentals](00_pytorch_fundamentals.ipynb)  
- 📒 [Chapter 1: PyTorch Workflow](01_pytorch_workflow.ipynb)  
- 📒 [Chapter 2: Classification in PyTorch](02_pytorch_classification.ipynb)  
- 📒 [Chapter 3: Computer Vision in PyTorch](03_pytorch_computer_vision.ipynb)  
- 📒 [Chapter 4: Custom Datasets in PyTorch](04_pytorch_custom_dataset.ipynb)
- 📒 [Chapter 5: Going Modular in PyTorch](05_pytorch_going_modular.ipynb)

---

## 🌱 About This Repo

This repository is a part of my ML/Deep Learning growth — documenting core PyTorch concepts through practical notebooks. The goal is not just to implement, but to **understand every line of code** and make learning reproducible for others.

---

## 📫 Connect With Me

📧 **Email**: akankshaj2002@gmail.com  
