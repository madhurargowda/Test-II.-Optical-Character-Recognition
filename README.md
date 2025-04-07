# Test-II.-Optical-Character-Recognition
Google summer of code test 2
CRNN + CTC OCR Model for Historical Spanish Documents

This project implements an Optical Character Recognition (OCR) system designed for historical Spanish documents using a Convolutional Recurrent Neural Network (CRNN) with Connectionist Temporal Classification (CTC) loss. It is built using TensorFlow and trained on synthetic data derived from real document transcriptions.
Key Features

    Preprocessing pipeline to simulate training images from historical text

    CRNN model combining CNNs + Bidirectional LSTMs

    CTC loss function for sequence alignment without explicit segmentation

    Visualizations for training performance and label decoding

    Easy to deploy and train on Google Colab
    Tech Stack

    TensorFlow / Keras

    OpenCV / PIL for image simulation

    NumPy and Matplotlib for visualization
     Getting Started

    Clone the repo

    Install dependencies:

pip install -r requirements.txt

Run the notebook ocr_crnn_ctc_model.ipynb on Colab or locally.
