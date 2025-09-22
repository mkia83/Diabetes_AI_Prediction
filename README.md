# Diabetes_AI_Prediction
A Machine learning model to predict Diabetes from Diabetes dataset
 📋 Project Overview

This project implements a neural network model to predict diabetes based on clinical parameters. The model serves as a proof-of-concept for AI-assisted medical screening tools.

*Key Features:*
- Binary classification of diabetes risk
- Deep neural network with dropout regularization
- Comprehensive model evaluation metrics
- Easy-to-use prediction interface

## 🏗️ Model Architecture

Model: "sequential_6"
_________________________________________________________________
 Layer (type)                Output Shape              Param #   
=================================================================
 dense_30 (Dense)            (None, 256)               2304      
                                                                 
 dropout_18 (Dropout)        (None, 256)               0         
                                                                 
 dense_31 (Dense)            (None, 128)               32896     
                                                                 
 dropout_19 (Dropout)        (None, 128)               0         
                                                                 
 dense_32 (Dense)            (None, 64)                8256      
                                                                 
 dropout_20 (Dropout)        (None, 64)                0         
                                                                 
 dense_33 (Dense)            (None, 128)               8320      
                                                                 
 dense_34 (Dense)            (None, 1)                 129       
                                                                 
=================================================================
Total params: 51905 (202.75 KB)
Trainable params: 51905 (202.75 KB)
Non-trainable params: 0 (0.00 Byte)
