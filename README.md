# **Yoga Pose Classification using MobileNetV3**  
*(A deep learning project for classifying yoga poses using a CNN based on MobileNetV3.)*


## Introduction

This project implements a convolutional neural network (CNN) using the MobileNetV3 architecture to classify yoga poses. The model is trained on a dataset sourced from Kaggle and produces a trained model saved in `.h5` format for future use.


## Dataset
The dataset is sourced from Kaggle. You can download it [here](https://www.kaggle.com/datasets/tr1gg3rtrash/yoga-posture-dataset) and place it in the `data` directory. Ensure the dataset is organized into proper train/test folders.


    
## Installation

Follow these steps to set up the project:  

1. Clone the repository:  
   ```bash
   git clone https://github.com/EdrichCardozo06/PoseDetect-CNN_Mobilenetv3.git
   cd PoseDetect-CNN_Mobilenetv3 ;

2. Create Enviroment(.env) and install the dependances  (requirements.txt):
   ```bash
   python -m venv .env
   .env/Scripts/activate 
   pip install -r requirements.txt;                                                                                               
3. Open the `yoga-pose-classification-using-cnn-mobilenetv3.ipynb` and elect the .env file as the kernel .

4. The Model get saved as ` my_model_final.h5 ` in Project Directory .
5. To test the model run the last code snippet in `yoga-pose-classification-using-cnn-mobilenetv3.ipynb` .
## Features
 
- Efficient model training using MobileNetV3.  
- Classification of various yoga poses.  
- Reusable model saved in `.h5` format.  
- Helper functions for preprocessing and evaluation in `helper.py`.  


**Sample Pose Prediction Output:**<br>
<p align="center">
  <img src='https://user-images.githubusercontent.com/88816150/189837009-a7344d98-d795-4bc4-b1fd-640e772221f7.gif' alt="Pose" />
</p>
**Final Output after model is trained:**<br>
<p align="center">
  <img src='https://github.com/EdrichCardozo06/PoseDetect-CNN_Mobilenetv3/blob/main/Results/model_results.png' alt="model_accuracy" />
</p>

