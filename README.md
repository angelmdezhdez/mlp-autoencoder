# **Autoencoder with MLP Applied to MNIST**  
_This project implements an autoencoder using a multilayer perceptron (MLP) with sigmoid activations. The quality of digit image reconstruction is evaluated using the MNIST dataset.
Although, it includes a version with the typical problem of clasification._

---

## **Description**  
This project implements a basic autoencoder with the following features:  
- Uses the MNIST dataset (handwritten digit images).  
- The autoencoder is designed with sigmoid activations to compress the images into a reduced feature space and then reconstruct them.  
- Visualizes the reconstruction quality for the digits in the test set.  

The autoencoder is a simple way to explore compact representation and unsupervised learning in neural networks.

---

## **Main Features**  
- Training on the MNIST dataset.  
- Sigmoid activations for encoding and decoding.  
- Visual evaluation of the reconstructions.  

---

## **Prerequisites**  
- Python >= 3.8.  
- Required libraries:  
  - `numpy`  
  - `scikit-learn`  
  - `matplotlib`  

---

## **Installation**  
Steps to set up and run this project:  
1. Clone this repository:  
   ```bash
   git clone https://github.com/angelmdezhdez/mlp-autoencoder.git
