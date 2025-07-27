**Low-Light Image Enhancement**

This project aims to enhance low-light images using a deep learning model. The implementation is based on the research paper **"Zero-Reference Deep Curve Estimation for Low-Light Image Enhancement"** and utilizes the **LOL dataset.**

**📝 Table of Contents**

1. Objective
2. Dataset
3. Methodology
4. Getting Started
5. Results

**🎯 Objective**

The primary goal of this project is to improve the visual quality of images captured in low-light environments. By applying a deep learning-based approach, the model learns to adjust the image's brightness, contrast, and color balance to reveal details that are otherwise hidden in the dark.

**💾 Dataset**

This project uses the LOL (Low-Light) dataset, which contains pairs of low-light and normal-light images. This dataset is crucial for training and evaluating the performance of the enhancement model.

You can download the dataset from Kaggle:

Dataset Link: https://www.kaggle.com/datasets/soumikrakshit/lol-dataset

**🛠️ Methodology**

The core of this project is the implementation of the architecture proposed in the research paper:

Zero-Reference Deep Curve Estimation for Low-Light Image Enhancement

This paper introduces a novel method for low-light image enhancement that does not require paired training data, making it a "zero-reference" approach. It works by estimating a high-order curve for each pixel to adjust the image's dynamic range.

Paper Link: https://arxiv.org/abs/2001.06826

**🚀 Getting Started**

Follow these steps to set up the project on your local machine.

**Prerequisites**

Make sure you have the following installed:
Python 3.x

TensorFlow or PyTorch

OpenCV

NumPy

Matplotlib


You can install the required Python packages using pip:

Bash

**pip install tensorflow opencv-python numpy matplotlib**

or

Bash

**pip install torch torchvision torchaudio opencv-python numpy matplotlib**


Download the Dataset:

Download the LOL dataset from the Kaggle link provided above.
Upload to Google Drive:
Upload the dataset folder to your Google Drive.
Update the Code:

Open the main project file (e.g., zero_dce.ipynb).

Locate the variable that defines the path to the dataset.

Update this path to point to the location of the LOL dataset folder in your Google Drive. 

**✨ Results**

Here you can showcase some examples of low-light images before and after enhancement using your model.

<img width="1153" height="251" alt="image" src="https://github.com/user-attachments/assets/42a4ea1e-81ff-4c60-aab8-01154ca81150" />

