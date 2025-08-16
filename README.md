# Battle of the Neural Networks: DNNs vs. CNNs in Image Classification

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1dMzwZSTSasuxYhhGs8hB2t4QGoFG71Au)

*Click the badge above to explore the full notebook and run the code.*

## Project Overview
There's something electric about training a neural network, watching the epochs pour down your screen, tracking the accuracies and losses in real-time. That's exactly what we'll be doing in this project. 

We’ll be pitting **fully connected deep neural networks (DNNs)** -- multi-layer perceptrons that flatten images -- against **convolutional neural networks (CNNs)** that preserve spatial structure for an image classification task using the popular [CIFAR-10 dataset](https://www.cs.toronto.edu/~kriz/cifar.html), which consists of 60,000 32x32 color images split into 10 classes:

- Airplane
- Automobile
- Bird
- Cat
- Deer
- Frog
- Horse
- Ship
- Truck

**Spoiler alert**: The CNNs win -- after all, image classification is exactly the sort of task they excel at. But along the way, we'll find out *why* this is the case.

Time for the deep dive.

## Tools & Libraries Used

- **Google Colab (with GPU runtime)** - cloud-based environment for writing and running the notebook with hardware acceleration
- **Python 3.11.13** - base language powering the project
- **Keras** - for loading CIFAR-10, building DNN and CNN models, training, and evaluation

## Acknowledgments

This notebook builds on a project from Professor Tao Li’s Machine Learning with Python course at the Leavey School of Business at Santa Clara University. Many thanks to Professor Li for the lectures that spark further exploration.
