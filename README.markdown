# Machine Learning Course Project

This repository contains the project work completed as part of the Machine Learning course at the university. The project focuses on implementing an ensemble approach for image classification using four distinct deep learning models: **ViT**, **ResNet**, **EfficientNet**, and **MobileNet**. Below is a summary of the project's methodology and structure.

## Project Overview

### Ensemble Approach
The project employs an ensemble strategy combining four models—ViT, ResNet, EfficientNet, and MobileNet—to enhance classification accuracy. Each model's output is weighted based on its performance on the test dataset, using a performance-based weighting formula to determine the final classification result. This approach leverages the diverse feature extraction capabilities of the models to improve robustness and accuracy.

### Transfer Learning
All models utilize pre-trained weights from ImageNet as their initial weights. These weights are fine-tuned during training with various parameter combinations and data augmentations to optimize validation accuracy.

### Best Weights Preservation
During training, model weights are saved whenever a new highest validation accuracy is achieved. This ensures that the best-performing model states are preserved for further evaluation and fine-tuning.

### Phase Planning
The project is divided into two phases:
- **Phase 1: Experiments** - Train models with simple augmentations and varying hyperparameters (e.g., learning rates, weight decays) to assess their performance and behavior.
- **Phase 2: Adjustments** - Refine models based on TA-provided accuracy results and observed behaviors from Phase 1, incorporating individualized optimization strategies.

### Work Distribution
Each team member is responsible for training two models in both phases. After receiving TA feedback, members will analyze performance and apply unique approaches to refine their models, fostering diverse training techniques and hyperparameter tuning.