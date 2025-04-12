# Binary Image Classification Using Deep Neural Networks 

This notebook contains implementation of shallow, 2-layer, and 5-layer deep neural networks for binary image classification using a custom HDF5 dataset derived from the CIFAR-10 dataset.

## 🧪 Potential Classification Scenarios
The same deep learning setup can be used for other binary classification tasks such as:
- Dog vs. Non-dog
- Car vs. Non-car
- Human Face vs. Non-human Face
- Chair vs. Non-chair
- Bike vs. Non-bike
- Motorcycle vs. Non-motorcycle
- Day vs. Night
- Healthy vs. Unhealthy Plant
- ✅ Cat vs. Non-Cat (Implemented here)

## 📌 Classification Task
**Cat vs. Non-Cat** – The model is trained to distinguish between images of cats and other objects using labeled image data.

## 🗂️ Dataset
- Format: HDF5 (`.h5`)
- Source: [CIFAR-10 dataset](https://www.cs.toronto.edu/~kriz/cifar.html)
- Each image: RGB format with shape `(num_px, num_px, 3)`
- Training/Test set: Preprocessed and saved into `data.h5`

## 🚀 Technologies Used
- Python
- NumPy
- h5py
- matplotlib
- Deep Learning (from scratch using NumPy)

## 📁 Included Files
- `Binary_Classification_DNN.ipynb`: Notebook with full implementation and data preparation

