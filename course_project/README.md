# Building segmentation on aerial images
This is the code for my attempt at task 1 in the [MapAI](https://github.com/Sjyhne/MapAI-Competition/tree/master) competition. This is my project for the course IKT452 held at the University of Agder, Grimstad.

## Competition
The competition can be found [here](https://www.nora.ai/competition/mapai-precision-in-building-segmentation/index.html), and was finished in desember of 2022. I worked on this project between march-may 2023.
The competition consists of two tasks. Task 1 is building segmentation using aerial photos, and Task 2 is to do the same using LiDar scans.
For this project I have only solved Task 1.

## Implementation
To run this project, just run the notebook. It is recommended to use a GPU. The best results I achieved was with the model stored in the models directory. 

The model architecture is U-Net.

## Dataset
The dataset used was provided by the competition. It contains a training set and a validation set.

## Results
The competition evaluates the results using IoU and BIoU.
The results I achieved was validated by getting the IoU and BIoU on the validation part of the dataset.

I achieved these results:
Score: 0.810140289508601, iou: 0.8895996830636844, biou: 0.730680895953518

This is better than the first place of the competition on Task 1, which is why I am a bit unsure if everything is correct.