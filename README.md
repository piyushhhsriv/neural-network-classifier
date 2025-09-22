# Neural Network Classifier: Letters A, B, and C

## Overview

This project implements a simple feedforward neural network from scratch using only NumPy, to classify binary 5×6 images of the capital letters A, B, and C. The purpose is to gain hands-on practice with neural network fundamentals such as forward propagation, backpropagation, weight updates, and performance metrics without relying on machine learning libraries.

## Approach

- **Data Preparation:** Each letter (A, B, C) is encoded as a binary 5×6 pattern, flattened to a 30-length vector.
- **Neural Network:** 1 hidden layer, sigmoid activations, trained via backpropagation.
- **Training:** The network is trained to minimize cross-entropy loss, tracking accuracy and loss over epochs.
- **Visualization:** Training curves and letter predictions shown via `matplotlib`.

## Key Files

- `neural_network_letters.ipynb`: Main code notebook for model, training, and testing.

## Key Findings

- The neural network can successfully learn to distinguish between the letters A, B, and C from their pixelated representations.
- Visualizing loss and accuracy demonstrates effective learning.

---

## How to Run

1. Clone this repo.
2. Open `neural_network_letters.ipynb` in Jupyter Notebook.
3. Run all cells.

---

## Author

*Piyush Srivastava* | [GitHub](https://github.com/yourprofile)
