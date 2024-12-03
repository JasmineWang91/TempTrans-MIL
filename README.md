# Robotic Palpation Dataset for Tumor Depth Estimation

This dataset is designed for simulating a tumor depth estimation task using robotic palpation. The dataset was collected from experiments where tumors with hard inclusions are simulated, and phantom tissue is fabricated from silicone. The experiments were conducted using the **BarrettHand sensor**, which provides detailed tactile feedback and torque measurements for each of its three fingers during the palpation process.

The task is formulated as a **12-class classification problem**, where each class represents a specific depth of the tumor within the phantom tissue. This dataset can be used for developing, training, and testing machine learning models for tactile-driven robotic manipulation and tumor depth estimation.

## Robotic Palpation Experiment Overview

- **Task Type**: 12-class classification problem
- **Sensor Used**: BarrettHand tactile sensor
- **Tumor Simulation**: Simulated tumors with hard inclusions
- **Phantom Tissue**: Fabricated from silicone
- **Number of Classes**: 12 (each representing a specific tumor depth)
- **Features**: Tactile array data and torque data from the three fingers of the BarrettHand sensor
- **Application**: Tumor depth estimation via robotic palpation

## Dataset Features

The dataset consists of tactile array data and torque measurements captured by the BarrettHand sensor during the robotic palpation process. These measurements are taken from all three fingers of the BarrettHand during each palpation attempt. The dataset includes the following key features:

- **Tactile Array Data**: Pressure and displacement readings from the tactile sensors on each of the three fingers of the BarrettHand.
- **Torque Data**: Rotational force data for each of the three fingers, representing the amount of torque applied during the palpation.
- **Depth Label**: Each instance is labeled with one of 12 depth categories representing different tumor depths within the phantom tissue.

Each row represents a tactile reading and torque measurement for each of the three fingers, along with the corresponding depth label.

## Download Links

- **Dataset**: You can download the dataset from the following link:  
  [Download Robotic Palpation Dataset](https://www.dropbox.com/home/Robatic%20Palpation%20Dataset)
  
- **Video**: You can view and download the related video of the robotic palpation experiment:  
  [Download Robotic Palpation Experiment Video](https://www.dropbox.com/home/Robatic%20Palpation%20Dataset/Robotic%20Palpation%20Experiment%20Video)

## Usage

This dataset can be used for:

- Developing machine learning models for tactile-driven robotic manipulation
- Training models to estimate the depth of tumors based on robotic palpation
- Evaluating the performance of different algorithms for tumor depth classification
