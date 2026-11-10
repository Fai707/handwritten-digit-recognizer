# Handwritten Digit Recognizer
![MNIST_dataset_example](https://upload.wikimedia.org/wikipedia/commons/b/b1/MNIST_dataset_example.png)

A machine learning project that recognizes handwritten digits (0–9) using artificial neural networks and the MNIST dataset.

Developed in **2023 as part of a Mawhiba project**, this repository explores image classification, neural networks, and the fundamentals of deep learning.

## Overview

Handwritten digit recognition is a classic computer vision problem in which a machine learning model learns to identify numerical digits from images.

This project explores how neural networks can learn patterns from handwritten digits and use those patterns to classify new images.

### Project Objectives

- Understand the fundamentals of artificial neural networks.
- Explore image classification using the MNIST dataset.
- Train and evaluate a digit recognition model.
- Experiment with neural network architectures.
- Save and reuse trained machine learning models.

## Dataset

The project uses the **MNIST (Modified National Institute of Standards and Technology)** dataset.

MNIST contains 70,000 grayscale images of handwritten digits, divided into:

| Dataset | Images |
|---|---:|
| Training | 60,000 |
| Testing | 10,000 |
| Image dimensions | 28 × 28 pixels |
| Classes | 10 (digits 0–9) |

Each image represents a single handwritten digit.

## Technologies

- **Python** – Primary programming language
- **Jupyter Notebook** – Development and experimentation
- **Neural Networks** – Machine learning approach
- **MNIST** – Handwritten digit dataset
- **HDF5 (.h5)** – Saved model format

## Repository Structure

```text
handwritten-digit-recognizer/
├── model.ipynb       # Model development notebook
├── load.ipynb        # Model loading notebook
├── model04 .h5       # Saved trained model
└── README.md         # Project documentation
```

## Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/Fai707/handwritten-digit-recognizer.git
cd handwritten-digit-recognizer
```

### 2. Set Up a Python Environment

```bash
python -m venv .venv
```

Activate the environment:

**Linux/macOS:**

```bash
source .venv/bin/activate
```

**Windows:**

```powershell
.venv\Scripts\activate
```

### 3. Open the Notebooks

Install Jupyter:

```bash
pip install notebook
```

Start Jupyter Notebook:

```bash
jupyter notebook
```

Open `model.ipynb` to explore model development or `load.ipynb` to explore the saved model.

Install any additional dependencies imported by the notebooks before running them.

## Machine Learning Workflow

The project follows a typical machine learning workflow:

1. **Data Loading:** Load handwritten digit images from MNIST.
2. **Preprocessing:** Prepare image data for neural network input.
3. **Model Development:** Build a neural network for digit classification.
4. **Training:** Train the model using labeled digit images.
5. **Evaluation:** Evaluate the model using unseen test data.
6. **Model Saving:** Store the trained model for later use.
7. **Inference:** Load the model and classify handwritten digits.

## How It Works

The model takes an image of a handwritten digit as input and predicts which digit it represents.

**Input:** A grayscale image containing a handwritten digit.

**Processing:** The neural network analyzes learned visual patterns to estimate the digit class.

**Output:** A predicted digit between 0 and 9.

## What I Learned

This project provided hands-on experience with:

- Machine learning and neural network fundamentals.
- Computer vision and image classification.
- Working with image datasets.
- Training and evaluating predictive models.
- Saving and loading machine learning models.
- Developing machine learning experiments in Jupyter Notebook.

## Background

This project was developed in **2023 during my participation in Mawhiba**, as an early exploration of artificial intelligence and machine learning.

It represents one of my practical experiences in understanding how neural networks can be applied to real-world pattern recognition problems.

## Author

**Fai707**

GitHub: [github.com/Fai707](https://github.com/Fai707)

## Acknowledgments

- **Mawhiba** – Project learning experience
- **MNIST** – Handwritten digit recognition dataset
