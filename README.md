🚗 Lane Detection using SegFormer for Semantic Segmentation
A team project for detecting road lanes using the SegFormer architecture, applied on the BDD100K dataset. This project leverages semantic segmentation with PyTorch and HuggingFace Transformers to accurately detect lane markings.

📌 Project Overview
Timeline: Aug 2024 – Nov 2024

Role: Team Leader

Goal: Build a robust lane detection system using a deep learning model with semantic segmentation capabilities.

🧠 Model & Techniques
Architecture: SegFormer

Pre-trained weights used for transfer learning.

Optimizer: AdamW

Scheduler: Linear learning rate scheduler

Loss Function: Cross-entropy

📊 Dataset
BDD100K dataset

Custom split:

8,000 training images

2,000 validation images

🧪 Results
Mean IoU Score: 0.61

The model achieved consistent performance improvements through data augmentation and fine-tuning.

⚙️ Preprocessing Steps
Resized images to match input size of SegFormer.

Converted lane annotations to binary masks.

Applied data augmentation for robustness.

🧰 Tech Stack
Framework: PyTorch

Libraries: cv2, numpy, PIL, tqdm, transformers, requests, copy, os
