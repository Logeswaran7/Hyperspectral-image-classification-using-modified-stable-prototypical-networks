# Hyperspectral Image Classification Using Modified Stable Prototypical Networks

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Dataset](#dataset)
- [Model Architecture](#model-architecture)
- [Results](#results)
- [License](#license)

## Introduction
Hyperspectral imaging involves capturing and processing information across the electromagnetic spectrum. Unlike conventional imaging techniques, hyperspectral imaging captures data at different wavelengths, providing a wealth of information for various applications, including remote sensing, agriculture, and medical diagnostics.

This project introduces a novel approach for Hyperspectral Image (HSI) classification, addressing the challenges posed by limited labeled samples and the inaccessibility of hyperspectral data. Despite the success of deep learning frameworks, HSI classification models often struggle due to these limitations. To overcome these challenges, we propose a modified Stable Prototypical Network (SPN) that enhances overall model performance. 

The model constructs multiple class prototypes in a low-dimensional space and employs few-shot learning by calculating distances between prototypes and samples. Our architecture incorporates a new mathematical model, replacing the traditional approach to significantly boost performance. This new approach within the SPN framework offers several advantages, including effective cross-domain knowledge transfer, improved generalization, and reduced annotation issues. Experimental results demonstrate that our model excels in adaptability and resource management for HSI classification.

## Features
- **Modified Prototypical Networks**: Enhanced to provide better performance and stability.
- **Few-shot Learning**: Capable of classifying with limited training data.

## Installation
1. Clone the repository:
    ```bash
    git clone https://github.com/Logeswaran7/Hyperspectral-image-classification-using-modified-stable-prototypical-networks.git
    cd Hyperspectral-image-classification-using-modified-stable-prototypical-networks
    ```
2. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```
## Dataset
1.You can download the hyperspectral datasets in mat format at: http://www.ehu.eus/ccwintco/index.php/Hyperspectral_Remote_Sensing_Scenes

2.We conducted experiments using a limited subset of corrected dataset along with their corresponding ground truth labels, which have been included in the repository

## Model-architecture
1.To know about legacy prototypical model architecture you can refer to the paper at this link [Prototypical Networks for Few-shot Learning](https://arxiv.org/abs/1703.05175), introduced by Jake Snell, Kevin Swersky, and Richard Zemel in their December 2017 paper titled "Prototypical Networks for Few-shot Learning.
