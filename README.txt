# Handwritten-Digit-Recognition

Handwritten Digit Recognition

This project demonstrates a Convolutional Neural Network (CNN) built using PyTorch, trained on the MNIST dataset, to recognize handwritten digits (0–9). The trained model is deployed as a simple **Flask web app** that lets users upload or draw digits for prediction.

--------------------------------------------------------------------------------------------------------------------------------------------------------------

About the MNIST Dataset

The MNIST dataset (Modified National Institute of Standards and Technology) is one of the most popular benchmark datasets for image classification. It contains:
- 60,000 training images
- 10,000 test images
- Each image is a 28×28 pixel grayscale photo of a single handwritten digit (0–9)

Top-performing models using deep learning can reach **>99% accuracy** on this dataset.

------------------------------------------------------------------------------------------------------------------------------------------------------

Project Goal

The main objective is to:
- Build a CNN that accurately classifies handwritten digit images.
- Integrate the model into a **Flask web application** for easy interaction.
- Provide an intuitive user interface to upload an image and get the predicted digit.

------------------------------------------------------------------------------------------------------------------------------------------------------------

How to Run

Install Dependencies

Anaconda or `pip`:

```bash
# Using Conda (recommended)
conda create -n digit_recog_env python=3.10
conda activate digit_recog_env
conda install pytorch torchvision torchaudio cpuonly -c pytorch
pip install flask
--------------------------------------------------------------------------------------------------------------------------------------------------------------------
The handwritten digit recognition is the capability of computer
applications to recognize the human handwritten digits. It is a
hard task for the machine because handwritten digits are not
perfect and can be made with many different shapes and sizes.
The handwritten digit recognition system is a way to tackle this
problem which uses the image of a digit and recognizes the
digit present in the image.


