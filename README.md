# Electron-Photon-Classification


## Overview

This project focuses on classifying electrons and photons using deep learning models. The dataset consists of photon and electron events stored in HDF5 format. A ResNet-15 architecture is used for feature extraction and classification.

## Dataset

The dataset contains HDF5 files for photon and electron events. You can download the datasets from the following links:

- **Photons:** [Download](https://cernbox.cern.ch/index.php/s/AtBT8y4MiQYFcgc)
- **Electrons:** [Download](https://cernbox.cern.ch/index.php/s/FbXw3V4XNyYB3oA)

After downloading, place the files in the `dataset/` directory.

## Installation

### Prerequisites

Ensure you have the following installed:

- Python 3.8+
- TensorFlow
- Keras
- NumPy
- Matplotlib
- h5py
- Jupyter Notebook&#x20;

### Setting Up the Environment

```bash
git clone https://github.com/Rohit991371/Electron-Photon-Classification.git
cd Electron-Photon-Classification
```

## Usage

### Training the Model

Run the Jupyter Notebook to preprocess data and train the model:

```bash
jupyter notebook notebooks/Electron-Photon-Classification.ipynb
```

### Evaluating the Model

Once trained, the model can be evaluated using:

```python
model.evaluate(X_test, y_test)
```

## Repository Structure

```
.
├── notebooks/              # Jupyter Notebooks for training and evaluation
├── README.md               # Project documentation
```

## Contributing

Contributions are welcome! If you find issues or improvements, feel free to submit a pull request.


