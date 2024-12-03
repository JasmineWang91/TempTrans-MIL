# Robotic Palpation Dataset for Tumor Depth Estimation

This dataset is designed for simulating a tumor depth estimation task using robotic palpation. The data was collected from experiments where simulated tumors with hard inclusions are embedded in phantom silicone tissue. The experiments were conducted using the **BarrettHand sensor**, which provides detailed tactile feedback and torque measurements from each of the three fingers during the palpation process.

The task is formulated as a **12-class classification problem**, where each class corresponds to a specific tumor depth. The dataset and accompanying video can be used for developing, training, and testing machine learning models focused on tactile-driven robotic manipulation and tumor depth estimation.

## Download Links

- **Dataset**: You can download the dataset from the following link:  
  [Download Robotic Palpation Dataset](https://www.dropbox.com/home/Robatic%20Palpation%20Dataset)
  
- **Experiment Video**: You can view and download the related video of the robotic palpation experiment here:  
  [Download Robotic Palpation Experiment Video](https://www.dropbox.com/home/Robatic%20Palpation%20Dataset/Robotic%20Palpation%20Experiment%20Video)

## Robotic Palpation Experiment Overview

- **Task Type**: 12-class classification problem
- **Sensor Used**: BarrettHand tactile sensor
- **Tumor Simulation**: Simulated tumors with hard inclusions
- **Phantom Tissue**: Fabricated from silicone
- **Number of Classes**: 12 (representing different tumor depths)
- **Features**: Tactile array data and torque data from the three fingers of the BarrettHand sensor
- **Application**: Tumor depth estimation via robotic palpation

## Dataset Features

The dataset includes tactile array and torque data captured during the robotic palpation process. Data is collected from all three fingers of the BarrettHand sensor during each palpation attempt, with the following key features:

- **Tactile Array Data**: Pressure and displacement readings from the tactile sensors on each of the three fingers.
- **Torque Data**: Rotational force measurements for each of the three fingers, representing the amount of torque applied during the palpation process.
- **Depth Label**: Each sample is labeled with one of 12 depth categories, indicating the depth of the simulated tumor within the phantom tissue.

Each data point corresponds to the tactile readings and torque measurements for the three fingers, with the associated depth label indicating the tumor's depth.

## Usage

This dataset can be used for:

- Developing machine learning models for tactile-driven robotic manipulation
- Training models for tumor depth estimation based on robotic palpation
- Evaluating algorithms for tumor depth classification based on tactile sensor data
