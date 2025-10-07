# Project Notebooks

This project contains two main Jupyter notebooks:

## 1. code.ipynb

- Main notebook for running experiments, training models, or performing analysis related to the project.
- Building a classic CNN to be trained on unencrypted data in class `ConvNet`.
- Using the weights from `ConvNet` to update CKKS ready class `EncConvNet`.
- Running tests comparing the accuracy of each class.
- A smaller sample size is used for Encrypted inference as its computationally intensive.

## 2. encoder.ipynb

- Visualization of CKKS on a sample data object*
- Shows image array before encryption and after.

<sub><sup> * Actual CKKS object varies</sup></sub>
---

**Data Location:**
- MNIST dataset files are located in `data/MNIST/raw/`.

**Getting Started:**
1. Install required Python packages.
2. Open the notebooks in your preferred environment.
3. Run cells as needed.

**Note:**
- For details on each notebook, see the markdown cells within the notebooks themselves.
- Update dependencies as required by your code.
