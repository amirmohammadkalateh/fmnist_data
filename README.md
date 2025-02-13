# fmnist_data
# Fashion-MNIST

This repository contains the Fashion-MNIST dataset, a drop-in replacement for the classic MNIST handwritten digit dataset.  It's intended for benchmarking machine learning algorithms, especially image classification models.

## Dataset Description

Fashion-MNIST is a dataset of Zalando's article images.  It consists of 70,000 grayscale images in 10 categories, with 60,000 training images and 10,000 test images.  Each image is 28 pixels in height and 28 pixels in width, for a total of 784 pixels.

The 10 classes are:

| Label | Description |
|---|---|
| 0 | T-shirt/top |
| 1 | Trouser |
| 2 | Pullover |
| 3 | Dress |
| 4 | Coat |
| 5 | Sandal |
| 6 | Shirt |
| 7 | Sneaker |
| 8 | Bag |
| 9 | Ankle boot |

## Data Files

The dataset is typically provided in the following format (often compressed):

*   **train-images-idx3-ubyte.gz:** Training set images (60,000 samples)
*   **train-labels-idx1-ubyte.gz:** Training set labels (60,000 labels)
*   **t10k-images-idx3-ubyte.gz:** Test set images (10,000 samples)
*   **t10k-labels-idx1-ubyte.gz:** Test set labels (10,000 labels)
