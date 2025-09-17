🧩 Project Overview

This project introduces a lightweight, energy-efficient AI framework for medical imaging diagnosis. Using teacher-student knowledge distillation, it compresses models significantly while maintaining high diagnostic accuracy and clinical-grade explainability. The design prioritizes performance, sustainability, and interpretability, making it suitable for real-world clinical applications.

🚀 Highlights

Efficient Models: ~30% smaller models with minimal accuracy loss

High Accuracy: 97.12% CT scan classification performance

Eco-Friendly: 70% lower carbon footprint vs. standard approaches

Scalable: Tested on 25,000 augmented CT scan images

Transparent AI: Pixel-level attention maps for explainable decisions

🏗 Framework Architecture

Teacher-Student Knowledge Distillation:

Component	Role
Teacher Model – EfficientNetB0	Provides high-accuracy knowledge for transfer
Student Model – DSNet	Lightweight, fast, energy-efficient for deployment
Distillation Strategy	Traditional & multi-teacher approaches compared
Dataset	25,000 augmented CT scans
🔍 Explainability & Insights

Grad-CAM – Visual heatmaps highlighting influential regions

LIME – Local interpretable explanations for model decisions

Clinical Transparency – Pixel-level attention for trustable AI

🛠 Technologies Used

TensorFlow 2.8 – Primary deep learning framework

Keras – High-level neural network API

PyTorch – Support for experimentation & advanced features

Vision Transformers – For enhanced feature extraction

Grad-CAM & LIME – Model interpretability

📊 Performance Snapshot
Metric	Value
Accuracy	97.12%
Model Size Reduction	30%
Carbon Footprint Reduction	70%
Dataset Size	25,000 CT scans
🌿 Environmental Impact

This project demonstrates sustainable AI in healthcare by drastically reducing computational energy usage while maintaining clinical-grade performance.

📝 Current Status

The repository is under review. Full code release will follow post-paper publication.
