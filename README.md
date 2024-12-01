# Drowsiness-Detection Based on RGB camera and evolving Fuzzy model
This repository contains the implementation of a real-time Driver Drowsiness Detection System designed to enhance road safety. By leveraging cutting-edge deep learning models combined with Fuzzy Inference Systems (FIS) for interpretability and Neural Architecture Search (NAS) for optimization, this system offers a scalable, accurate, and efficient solution for detecting driver fatigue in diverse and challenging conditions.

## Features
**Baseline Models:** Implements and evaluates machine learning and deep learning models such as ResNet, InceptionV3, DenseNet121, CNN, SVM, Decision Tree, and Random Forest.
**Hybrid Models:** Enhanced versions of baseline models integrated with FIS and NAS, significantly improving detection accuracy, robustness, and interpretability.
**Real-World Adaptability:** Optimized for varying conditions, including low-light environments, occlusions, and diverse driver demographics.
**Comprehensive Visualization:** Training curves, confusion matrices, and performance metrics are provided to offer insights into model performance.

## Confusion Matrix
| | Predicted: Non-Drowsy |	Predicted: Drowsy | Total |
|--------------------|---------------------| ----------------- | ----- |
| Actual: Non-Drowsy | 4454 | 16 | 4470 |
| Actual Drowsy| 28 | 3861 | 3889 |
| Total| 4482 | 3877 | 8359 |

Additional visualizations like training curves and performance metrics are included in the project notebooks.

## Installation
To install the necessary dependencies, run:

'''
pip install -r requirements.txt
'''

Requirements
- Python 3.x
- TensorFlow
- Keras
- OpenCV
- NumPy
- Matplotlib
- scikit-learn
- Pandas
- Jupyter Notebook

## Dataset
This project utilizes the Driver Drowsiness Dataset (DDD), which contains labeled RGB images of drivers in drowsy and non-drowsy states. The dataset has been extensively preprocessed, including normalization, augmentation, and feature extraction, to ensure high-quality inputs for the models.

Note: The dataset is not included in this repository. Please download the dataset from its official source [Driver Drowsiness Dataset](https://www.kaggle.com/datasets/ismailnasri20/driver-drowsiness-dataset-ddd/data)

## Usage
1. Run the Notebooks: Open the notebooks in your preferred IDE and follow the steps for:
    a. Data preprocessing and augmentation
    b. Model training and evaluation
    c. Performance visualization
2. Adjust Parameters: Modify hyperparameters (e.g., learning rate, batch size) in the notebooks for custom experiments.
3. View Results: Use the provided confusion matrices and training curves to analyze the models’ performance.

## Roadmap
The project is actively maintained, and the following enhancements are planned for future releases:

1. Improved Low-Light Detection:
    - Develop advanced preprocessing techniques and models for better performance in low-light or occluded scenarios.
2. Extended Dataset:
    - Integrate additional publicly available datasets for better generalization.
    - Collect real-world driving data to enhance robustness.
3. Edge Device Optimization:
    - Optimize the system for deployment on edge devices (e.g., Raspberry Pi) by reducing computational complexity.
    - Evaluate power consumption and memory usage on low-power devices.
4. Advanced Hybrid Models:
    - Explore integrating other deep learning architectures with fuzzy logic to enhance interpretability and accuracy.
    - Experiment with Neural Architecture Search (NAS) for auto-generating optimal hybrid models.

## Contributing
We welcome contributions! To contribute:

1. Fork the repository.
2. Clone your fork and create a feature branch.
3. Commit your changes and push them.
4. Open a pull request for review.

Please ensure your changes are well-documented and pass all tests.

## Authors and Acknowledgments
Special thanks to the creators of the [Driver Drowsiness Dataset (DDD)](https://www.kaggle.com/datasets/ismailnasri20/driver-drowsiness-dataset-ddd/data) and all contributors to this project.


**Project Status**
This project is actively maintained. Updates and new features are planned for future releases.


