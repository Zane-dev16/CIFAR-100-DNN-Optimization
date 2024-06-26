# Deep Neural Network optimization for the CIFAR-100

## Overview

This repository, explores the challenges and solutions of training Deep Neural Networks (DNNs) on the CIFAR-100 dataset. Unlike the simpler CIFAR-10, CIFAR-100 presents a more complex classification task with 100 classes, making it a suitable candidate for deeper models. Wider models typically struggle with this complexity, thus needing the use of deeper architectures. Additionally, we focus solely on DNNs with the goal to achieve above 50% accuracy which is quite difficult without convolutional layers. 

# Repository Structure

The repository is organized as follows:
```bash
CIFAR-100-DNN-Optimization/
├── notebooks/
│ ├── dnn_problems.ipynb
│ ├── optimizers_and_lr_scheduling.ipynb
│ ├── dnn_regularization.ipynb
│ ├── transfer_learning.ipynb
├── data/
├── models/
├── README.md
├── .gitignore
├── LICENSE
└── requirements.txt
```

### Directory Structure Overview

1. **data/**: Contains the CIFAR-100 dataset files.

2. **notebooks/**: Jupyter notebooks for each stage of the analysis and training.
    - **dnn_problems.ipynb**: Notebook covering challenges such as vanishing/exploding gradients and dead ReLU neurons.
    - **optimizers_and_lr_scheduling.ipynb**: Notebook for optimizer analysis and learning rate scheduling experiments.
    - **dnn_regularization.ipynb**: Notebook focusing on regularization and dropout techniques.
    - **transfer_learning.ipynb**: Notebook for transfer learning from CIFAR-100 to CIFAR-10.
3. **models/**: All saved models throughout the notebooks
4. **README.md**: Readme file providing an overview of the repository.
5. **LICENSE**: License file for the repository.
6. **requirements.txt**: File listing dependencies for the project.
