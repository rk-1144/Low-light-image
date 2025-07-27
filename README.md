Low-Light Image Enhancement
This project aims to enhance low-light images using a deep learning model. The implementation is based on the research paper "Zero-Reference Deep Curve Estimation for Low-Light Image Enhancement" and utilizes the LOL dataset.

📝 Table of Contents
Objective

Dataset

Methodology

Getting Started

Usage

Results

Acknowledgments

🎯 Objective
The primary goal of this project is to improve the visual quality of images captured in low-light environments. By applying a deep learning-based approach, the model learns to adjust the image's brightness, contrast, and color balance to reveal details that are otherwise hidden in the dark.

💾 Dataset
This project uses the LOL (Low-Light) dataset, which contains pairs of low-light and normal-light images. This dataset is crucial for training and evaluating the performance of the enhancement model.

You can download the dataset from Kaggle:

Dataset Link: LOL Dataset

🛠️ Methodology
The core of this project is the implementation of the architecture proposed in the research paper:

Zero-Reference Deep Curve Estimation for Low-Light Image Enhancement

This paper introduces a novel method for low-light image enhancement that does not require paired training data, making it a "zero-reference" approach. It works by estimating a high-order curve for each pixel to adjust the image's dynamic range.

Paper Link: https://arxiv.org/abs/2001.06826

🚀 Getting Started
Follow these steps to set up the project on your local machine.

Prerequisites
Make sure you have the following installed:

Python 3.x

TensorFlow or PyTorch

OpenCV

NumPy

Matplotlib

You can install the required Python packages using pip:

Bash

pip install tensorflow opencv-python numpy matplotlib
or

Bash

pip install torch torchvision torchaudio opencv-python numpy matplotlib
Setup
Clone the repository:

Bash

git clone <your-repository-link>
cd <your-repository-directory>
Download the Dataset:

Download the LOL dataset from the Kaggle link provided above.

Upload to Google Drive:

Unzip the downloaded dataset.

Upload the dataset folder to your Google Drive.

Update the Code:

Open the main project file (e.g., main.py or your training script).

Locate the variable that defines the path to the dataset.

Update this path to point to the location of the LOL dataset folder in your Google Drive. For example:

Python

# Before
dataset_path = "/path/to/your/local/lol_dataset"

# After (example for Google Colab)
from google.colab import drive
drive.mount('/content/drive')
dataset_path = "/content/drive/MyDrive/lol_dataset"
🏃 Usage
Train the Model:

Run the training script to train the model on the LOL dataset.

Bash

python train.py
Enhance an Image:

Use the trained model to enhance a low-light image.

Bash

python enhance.py --image /path/to/your/low_light_image.png
✨ Results
Here you can showcase some examples of low-light images before and after enhancement using your model.

Before	After
Add a sample low-light image here	Add the corresponding enhanced image here
Add another sample low-light image	Add the corresponding enhanced image

Export to Sheets
🙏 Acknowledgments
This project is an implementation of the paper "Zero-Reference Deep Curve Estimation for Low-Light Image Enhancement" by Guo et al. We are grateful for their contributions to the field.

We would also like to thank the creators of the LOL dataset for providing a valuable resource for low-light image enhancement research.
