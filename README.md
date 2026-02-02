# GMM-EMM Image Segmentation

This project implements image segmentation using **Gaussian Mixture Models (GMM)** and the **Expectation Maximization (EM)** algorithm in **Python**. It supports both **RGB** and **grayscale (black-and-white)** images.

## Features

- Unsupervised image segmentation using GMM + EM
- Supports color and grayscale images
- User-defined number of segments
- Simple command-line execution

## Requirements

- Python 3.x
- NumPy
- OpenCV
- scikit-learn
- matplotlib

Install dependencies:

```bash
pip install numpy opencv-python scikit-learn matplotlib

## How to Run

Clone the repository and navigate to the project directory:

git clone https://github.com/barualee/GMM-EMM-Image-Segmentation.git
cd GMM-EMM-Image-Segmentation


Add the input image to the images/ folder.

Run the application:

python EMM.py


When prompted:

Enter the number of segments

Enter the image file name from the ./images folder
