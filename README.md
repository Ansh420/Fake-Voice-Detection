![images](https://github.com/user-attachments/assets/017d3bc8-48dd-4671-b017-8a6831e98f1b)

# Fake-Voice-Detection
## Introduction
This repository provides a Python implementation of a Conformer model for fake speech detection, trained on the ASVspoof2019 dataset. The Conformer model is a state-of-the-art neural network architecture that combines the strengths of convolutional neural networks (CNNs) and recurrent neural networks (RNNs), making it well-suited for tasks like speech recognition and audio classification.

## Prerequisites
Before you can run the code, ensure you have the following installed:

- Python 3.6 or later.
- NumPy.
- SciPy.
- TensorFlow or PyTorch.
- Librosa.
- tqdm.
## Dataset
The ASVspoof2019 dataset is required for training and evaluation. You can download it from the official ASVspoof website: 
http://www.asvspoof.org/index2019.html
![download](https://github.com/user-attachments/assets/c185e210-3a40-4410-8203-a6f8a5adaa51)
## Usage
$ Clone the Repository:

$ https://github.com/Ansh420/Fake-Voice-Detection.git

## Install Dependencies:

- pip install -r requirements.txt

## Prepare the Data:

Create a directory structure to organize your data. For example:
- data/
  
    ├── train/
  
    │   ├── genuine/
  
    │   └── spoof/
  
    └── test/
  
Place the **ASVspoof2019 dataset** files into the appropriate directories.


## Model Architecture
The Conformer model used in this project consists of the following components:

- **Convolutional Module**: Applies convolutional layers to extract local features from the input audio.
- **Attention Module**: Uses attention mechanisms to focus on important parts of the input sequence.
- **Feed-Forward Module**: A fully connected layer that transforms the features.
- **Positional Encoding**: Encodes positional information into the input sequence to help the model capture temporal dependencies.
![Screenshot 2024-09-17 070850](https://github.com/user-attachments/assets/fe954e44-7e05-4076-bd0b-87ad89549fd8)
