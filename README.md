# Potato Disease Classification

This repository contains the code and resources for the Potato Disease Classification project, which utilizes a machine learning model to identify various diseases in potato plants based on leaf images.

## Table of Contents
- [Overview](#overview)
- [Dataset](#dataset)
- [Model](#model)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Contributing](#contributing)
- [Acknowledgements](#acknowledgements)

## Overview
The Potato Disease Classification project aims to help farmers and agricultural experts quickly and accurately identify diseases affecting potato crops. By using a convolutional neural network (CNN) trained on images of potato leaves, the model can distinguish between healthy leaves and those affected by various diseases.

## Dataset
The dataset used for training and testing the model is sourced from the PlantVillage dataset. It contains images of potato leaves categorized into the following classes:
- Healthy
- Early Blight
- Late Blight

## Model
The model is a deep learning CNN implemented using TensorFlow and Keras. It is trained on the Potato Disease Classification dataset to achieve high accuracy in identifying the disease classes.

## Installation
To run this project locally, follow these steps:

1. Clone the repository:
    ```bash
    git clone https://github.com/ShrutiBhosale/Potato-Disease-Classification.git
    ```
2. Navigate to the project directory:
    ```bash
    cd Potato-Disease-Classification
    ```
3. Create and activate a virtual environment:
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
    ```
4. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```

## Usage
To classify potato leaf images, you can use the `potato-disease-classification.ipynb` notebook or the provided scripts.

1. **Notebook:**
    - Open `potato-disease-classification.ipynb` in Jupyter Notebook or JupyterLab.
    - Follow the steps in the notebook to load the model, preprocess images, and make predictions.

2. **Script:**
    - Run the script to classify images in a specified directory:
    ```bash
    python classify_potato_leaves.py --input_dir path_to_images
    ```

## Results
The model achieves an accuracy of approximately XX% on the test dataset. Below are sample predictions made by the model:

| Image         | Predicted Class | Confidence |
| ------------- | --------------- | ---------- |
| ![Healthy]    | Healthy         | 95%        |
| ![EarlyBlight]| Early Blight    | 92%        |
| ![LateBlight] | Late Blight     | 89%        |

## Contributing
Contributions are welcome! If you have any suggestions or improvements, feel free to open an issue or create a pull request.

## Acknowledgements
- [PlantVillage](https://plantvillage.psu.edu/) for providing the dataset.
- TensorFlow and Keras teams for their excellent libraries.

---

*This project was developed with the help of the `potato-disease-classification.ipynb` notebook.*

