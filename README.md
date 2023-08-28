# forestfiredetection
# Overview
    Welcome to the Git repository for our project on Forest Fire Detection using pre-trained ResNet and DenseNet CNN models. This project aims to leverage the power of deep learning to 
    detect forest fires in images using two popular pre-trained convolutional neural network architectures: ResNet and DenseNet.

# Table of Contents
# Introduction
# Installation
# Usage
# Dataset
# Pre-trained Models
# Results

# Introduction
   Forest fires pose a significant threat to the environment and safety of people. This project focuses on building an automated system to detect forest fires from images using stat of     the-art deep learning models. We employ ResNet and DenseNet architectures, which are known for their exceptional performance in image classification tasks.

# Installation
  To set up the project on your local machine, follow these steps:

# Clone the repository:

  git clone https://github.com/your-username/forest-fire-detection.git
  cd forest-fire-detection

  python3 -m venv venv
  source venv/bin/activate
# Install the required dependencies:

  pip install -r requirements.txt
  
  python detect_forest_fires.py --image_path path/to/your/image.jpg
# Dataset
  We used a curated dataset of forest fire images for training and evaluation. The dataset is available at 'kaggle datasets download -d alik05/forest-fire-dataset'. Please refer to the dataset source for terms of use and 
  citation requirements.

# Pre-trained Models
   We utilize pre-trained ResNet and DenseNet models from popular deep learning frameworks such as TensorFlow and PyTorch. These models have been fine-tuned on our dataset for the 
   specific task of forest fire detection.

# Results
   Our trained models demonstrate impressive accuracy and performance in detecting forest fires in images. We achieved a validation accuracy of X% on our dataset. For detailed metrics 
   and visualizations, please refer to https://colab.research.google.com/drive/1nPHcAqf_cm2S-8vKJK1jORTHPVTG2Hsb?usp=sharing.
