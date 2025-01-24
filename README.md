# Dog Breed Classifier using Pre-trained CNN Models

This project implements a Python-based solution for classifying dog images using pre-trained Convolutional Neural Network (CNN) models: AlexNet, VGG, and ResNet. The system distinguishes between dog and non-dog images and identifies dog breeds, focusing on building supporting functions for model inference. The VGG model demonstrated the highest accuracy among the evaluated models.

## Features
- **Model Inference Support:** Implemented helper functions for image preprocessing, label extraction, and post-inference validation.
- **Command-Line Interface (CLI):** Integrated command-line arguments for flexibility in input directories, model selection, and dog name files.
- **Multiple Pre-trained Models:** Utilized AlexNet, VGG, and ResNet to evaluate classification accuracy and runtime performance.
- **Performance Comparison:** Analyzed model results to determine the most accurate classifier, with VGG outperforming AlexNet and ResNet.

### Python: Primary programming language for all implementations.
### Pre-trained Models:
- AlexNet
- VGG
- ResNet

## Setup
```bash 
install python, torch, numpy
```
## To Run this code Locally
- Go to the data folder by using `cd data` command in terminal.
- Then write this command `sh run_models_batch.sh` to perform classification on provided dataset.
- If you want to upload your own custom data to perform classification using these three models, then you have to upload you images into **uploaded_images** folder and run this command `sh run_models_batch_uploaded.sh` in terminal. It will execute the inference on your uploaded data.  

 ## Results
The VGG model achieved the best classification accuracy compared to AlexNet and ResNet.
