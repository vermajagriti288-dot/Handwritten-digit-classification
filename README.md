# Handwritten-digit-classification
Handwritten digit classification using PyTorch and the MNIST dataset, including data preprocessing, tensor conversion, GPU support, and visualization.
# MNIST Digit Classification using PyTorch

A deep learning project for classifying handwritten digits from the **MNIST dataset** using **PyTorch**.

## Project Overview

This project demonstrates the basic workflow for preparing the MNIST handwritten-digit dataset for a PyTorch-based classification task. The notebook loads the dataset, preprocesses and normalizes the images, converts the data into PyTorch tensors, checks the computation device, inspects the training data, and visualizes sample images.

## Dataset

The project uses the **MNIST handwritten digit dataset**.

- Training samples: 60,000
- Test samples: 10,000
- Image dimensions: 28 × 28 pixels
- Number of classes: 10 (digits 0–9)

The MNIST dataset is loaded using TensorFlow/Keras.

## Technologies Used

- Python
- PyTorch
- TensorFlow / Keras
- Pandas
- Scikit-learn
- Matplotlib

## Project Workflow

1. Load the MNIST dataset.
2. Check the training and testing data shapes.
3. Flatten the 28 × 28 images into 784 features.
4. Normalize pixel values to the range 0–1.
5. Convert the data into PyTorch tensors.
6. Set a random seed for reproducibility.
7. Detect and use GPU when available.
8. Inspect the processed training data.
9. Visualize sample handwritten digits.

## Notebook

The main implementation is available in:

`MNIST_Digit_Classification_PyTorch_GitHub_Ready.ipynb`

## How to Run

### Option 1: Google Colab

Upload the notebook to Google Colab and run the cells from top to bottom.

### Option 2: Local Environment

Clone this repository and install the required dependencies:

```bash
pip install -r requirements.txt
```

Then open the notebook using Jupyter Notebook or JupyterLab.

## Project Structure

```text
MNIST-Digit-Classification/
│
├── MNIST_Digit_Classification_PyTorch_GitHub_Ready.ipynb
├── README.md
└── requirements.txt
```

## Notes

The notebook is designed as a learning-oriented mini project demonstrating MNIST data preparation and a PyTorch deep learning workflow.

Model performance metrics are not reported here because they were not included in the original notebook.
