# Brain Tumor Detection using Deep Learning

## Overview
This project focuses on detecting brain tumors from MRI images using deep learning techniques. Several models, including VGG-19, ResNet, KNN, KAN, and DBN, were evaluated to determine the most effective approach.

## Models and Accuracy
Below are the accuracy scores achieved by different models on training and test datasets:

| Model  | Training Accuracy | Test Accuracy |
|--------|------------------|--------------|
| VGG-19 | 0.9703           | 0.902        |
| ResNet | 0.6089           | 0.6471       |
| KNN    | 0.5              | 0.5          |
| KAN    | 0.9208           | 0.8627       |
| DBN    | 0.4703           | 0.451        |

## Project Files
The repository contains the following files:
KAN.ipynb - Implementation of KAN model.
VGG19.ipynb - Implementation of VGG-19 model.
KNN (1).ipynb - Implementation of KNN model.
RESNET.ipynb - Implementation of ResNet model.
DBN.ipynb - Implementation of DBN model.

## Results and Observations
- *VGG-19* performed the best with *90.2% test accuracy*, indicating its strong feature extraction capability.
- *KAN* also showed promising results with *86.27% test accuracy*.
- *ResNet* had lower accuracy, possibly due to insufficient fine-tuning.
- *KNN* and *DBN* underperformed, suggesting they are not ideal for this task.

## Future Improvements
- Hyperparameter tuning for better model performance.
- Data augmentation to improve generalization.
- Trying additional architectures like EfficientNet or transformers.
