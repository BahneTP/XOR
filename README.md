# 5-Bit XOR Neural Network Implementation

## Background
This repository hosts the implementation of a Multi-Layer Perceptron (MLP) to solve the 5-input XOR problem, which is an excellent benchmark for testing the capability of neural networks to handle non-linear relationships. The 5-bit XOR problem evaluates the network's performance based on the parity of ones in the input, where the output is 1 if the number of 1s is odd, and 0 if it's even. This project was created as part of a research effort to explore neural network behaviors with varying architectures and loss functions.

## Features
- **Dataset Creation**: Automatic generation of a dataset comprising all possible binary permutations of five bits.
- **MLP Model**: Implementation of a multi-layer perceptron with customizable layers and neurons.
- **Activation and Loss Functions**: Utilization of sigmoid activation and both Binary Cross-Entropy (BCE) and Mean Squared Error (MSE) as loss functions.
- **Training and Evaluation**: Detailed training process with metrics visualization to assess model performance under different configurations.

```bash
# Clone the repository
git clone https://github.com/BahneTP/XOR.git
cd XOR
