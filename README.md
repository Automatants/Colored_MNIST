# Colored MNIST Challenge

The Colored MNIST Challenge involves classifying images of colored digits. The goal is to train a model that can accurately classify these digits based on the provided training and testing datasets.

## Dataset

The dataset consists of colored images of digits along with their corresponding labels. The dataset files are provided in `.gz` format.

- `colored_mnist_images.gz`: Training images
- `colored_mnist_targets.gz`: Training labels
- `colored_mnist_test_images.gz`: Test images

## Files

- `colored_mnist_images.gz`: Contains the training images in compressed format.
- `colored_mnist_targets.gz`: Contains the training labels in compressed format.
- `colored_mnist_test_images.gz`: Contains the test images in compressed format.
- `Colored_MNIST_challenge.ipynb`: Baseline Jupyter notebook for the challenge.

## Getting Started

1. **Clone the Repository**

   Clone the repository to your local machine:

   ```bash
   git clone https://github.com/Automatants/Colored_MNIST.git
   ```

2. **Install Dependencies**

    If you don't want to install all the dependencies on your machine, create a virtual environment :

    ```bash
    python -m venv .venv
    ```

    To activate the venv : 

    Windows :
    ```bash
    source .venv/Scripts/activate
    ```
    
    macOS/Linux :
    ```bash
    source .venv/bin/activate
    ```

    To deactivate the venv :

    ```bash
    deactivate
    ```

    Use the requirements.txt file to install the dependencies :

    ```bash
    pip install -r requirements.txt
    ```