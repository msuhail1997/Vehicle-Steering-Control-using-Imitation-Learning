# Steering Control using Imitation Learning

## The problem statement was solved with Behavioral Cloning, a simple type of Imitation Learning.

This file is for data and simulator download



1) Please download data from this url: https://www.kaggle.com/zaynena/selfdriving-car-simulator

You will download  "dataset" directory containing two sub-directories- "track1data" and "track2data".
These two directories correspond to the datasets of two diffferent terrains.

2) To download the simulator go to this url: https://github.com/udacity/self-driving-car-sim
(We used the Version 2 simulators)


*******************************************

The models implemented were:
* Support Vector Regression- ML baseline
* CNN for One-shot learning - DL baseline
* MTL (Multi-Task Learning) for Speed Control
* Few-Shot Learning model
* Transfer Learning

A comparitive study was done between 5 models.
For each model, we have provided a README.md file to help run that module.

In general,
model.py contains the model
train.py contains the training and validation loop
utils.py contains helper functions
drive.py is used for running the model on the simulator
