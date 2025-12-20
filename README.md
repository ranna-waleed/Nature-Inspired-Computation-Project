# Nature-Inspired-Computation-Project

Project Overview

This project integrates Nature-Inspired Computation (NIC) techniques with Deep Learning and Explainable AI (XAI) to develop an optimized and interpretable Convolutional Neural Network (CNN) model for classifying brain tumors from MRI images. The dataset used is the Brain Tumor MRI Dataset from Kaggle, containing 7023 images classified into 4 classes: glioma, meningioma, notumor, and pituitary.

# The project follows mandatory steps:

Step 1: Model Parameter Optimization - Tune CNN hyperparameters using 6 metaheuristic algorithms: Tabu Search, Particle Swarm Optimization (PSO), Simulated Annealing (SA), Hill Climbing, Grey Wolf Optimizer (GWO), and Whale Optimization Algorithm (WOA).

Step 2: Algorithm Parameters Optimization - Use Cuckoo Search to tune parameters of two selected algorithms (GWO and WOA).

Step 3: Explainability Optimization (XAI) - Optimize parameters of XAI techniques (LIME, Grad-CAM, and planned for SHAP or others) using 4 metaheuristics: Tabu Search for LIME, PSO for Grad-CAM, and planned WOA and GWO for additional XAI methods.

Unique algorithms used across steps: Tabu Search, PSO, SA, Hill Climbing, GWO, WOA, Cuckoo Search (7 total, no repetitions across stages).


Python 3.8+
Libraries: TensorFlow/Keras, NumPy, Pandas, Scikit-learn, Matplotlib, Seaborn, SHAP, LIME, Grad-CAM implementations, and metaheuristic libraries (e.g., PySwarms for PSO, or custom implementations).

Dataset: [Download from Kaggle Brain Tumor MRI Dataset](https://www.kaggle.com/datasets/masoudnickparvar/brain-tumor-mri-dataset).

# Installation

Clone the repository:textgit clone https://github.com/ranna-waleed/Nature-Inspired-Computation-Project
cd nic-brain-tumor-project
Download and preprocess the dataset:
Place images in data/Training/ and data/Testing/ folders.
Run preprocessing script: python preprocess.py (resizes images and handles margins).

# Results Summary

Baseline CNN: Test Accuracy ~77.65%

Optimized models: See comparison table in the project report.

Visualizations: Confusion matrices, Grad-CAM heatmaps, LIME explanations in results/ folder.
