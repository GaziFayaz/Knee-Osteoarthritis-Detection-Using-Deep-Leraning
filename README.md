# Knee Osteoarthritis Detection Using Deep Learning

This repository contains notebook-based deep learning experiments for three-class knee osteoarthritis image classification. The project uses a ResNet-50 transfer-learning workflow, image data generators, saved model loading, and evaluation notebooks.

## Features

- ResNet-50 transfer-learning notebook for three-class knee osteoarthritis classification.
- Notebook for loading a saved model and running evaluation workflows.
- Image preprocessing with Keras image data generators and ResNet preprocessing.
- Training support with Keras callbacks including early stopping and model checkpointing.
- Evaluation with confusion matrix and classification report.
- Visualization of model accuracy and loss using saved graph images.
- Google Colab-oriented notebook cells for Drive-mounted datasets.

## Tech Stack

- Python, Jupyter Notebook, Google Colab
- TensorFlow, Keras, ResNet50
- NumPy, pandas
- Matplotlib, Seaborn
- scikit-learn metrics: confusion matrix, classification report
- PIL, OpenCV, IPython display utilities

## Getting Started

Prerequisites:

- Python 3.10 or newer, or Google Colab
- Jupyter Notebook/JupyterLab for local execution
- Knee osteoarthritis image dataset arranged for Keras image generators

Create and activate a virtual environment for local execution:

```bash
python -m venv .venv
source .venv/bin/activate
```

Install notebook dependencies:

```bash
pip install jupyter tensorflow numpy pandas matplotlib seaborn scikit-learn pillow opencv-python
```

Start Jupyter:

```bash
jupyter notebook
```

Open the notebooks in this order:

```text
ResNet_50_3_class (1).ipynb
loaded_resnet_model_3_class.ipynb
```

If running in Google Colab, update the Drive mount paths in the notebooks so they point to your dataset location.

## Environment Variables

No environment variables are required. Dataset paths are configured inside the notebooks.
