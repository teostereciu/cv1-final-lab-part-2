# CV1 Final Lab Part 2

This repository contains the Jupyter Notebook for **Final Lab (Part 2)** of the **Computer Vision 1** course, part of the **Master's in Artificial Intelligence** program at the **University of Amsterdam**. The lab exercises are designed to deepen your understanding of key computer vision concepts and provide hands-on experience with popular Python libraries such as OpenCV, NumPy, and Matplotlib.

## Table of Contents

- [Overview](#overview)
- [Environment Setup](#environment-setup)
- [File Structure](#file-structure)

## Overview

Digital cameras are everywhere, embedded in consumer cameras, webcams, mobile phones, and professional equipment. These devices generate vast amounts of data, crucial for communication, observation, and interaction. This course focuses on the computational techniques used to enable computers to understand the visual world, with a particular emphasis on scene understanding and object recognition.

The course covers a wide range of topics, including:
- Image formation and filtering
- Feature extraction (color and shape invariants, interest point detectors, descriptors like SIFT and HoG)
- Visual information representation (vector space, statistical models, Bag-of-Words)
- Learning and classification techniques, including deep learning (DL)
- Object detection and classification, object tracking

## Environment Setup

This project requires a specific Conda environment to ensure all dependencies are properly installed. Follow the instructions below to set up the environment.

### Prerequisites

Make sure you have [Anaconda](https://www.anaconda.com/products/distribution) or [Miniconda](https://docs.conda.io/en/latest/miniconda.html) installed on your machine.

### Creating the Conda Environment

1. **Open a terminal**: Launch a terminal window (Anaconda Prompt, Command Prompt, or any terminal application).

2. **Navigate to the project directory**: Change to the directory where your `env.yaml` file is located:
   ```bash
   cd path/to/your/project/cv1-final-lab-part-2

3. **Create the Conda environment** *38final*:
    ```bash 
    conda env create -f env.yaml

4. **Activate the environemnt**:
    ```bash
    conda activate 38final

## File Structure

```markdown
cv1-final-lab-part-2/
│
├── .gitignore
├── 15732592_15743063_14836459_15494349.ipynb
├── LICENSE
└── README.md
│
├── models/  
│   └── twolayernet.pth
│   └── basic_convnet.pth
│   └── fourlayernet.pth
│   └── deeper_convnet.pth
│
└── results/  
│   └── twolayernet_results.json
│   └── basic_convnet_results.json
│   └── fourlayernet_results.json
│   └── deeper_convnet_results.json
```