## Overview

This project demonstrates handwriting digit recognition using the MNIST dataset. It is implemented in Python with TensorFlow and Keras and trained on the well-known MNIST dataset consisting of 70,000 handwritten digits (0–9).

The model is a Convolutional Neural Network (CNN) that achieves high accuracy in classifying handwritten digits. The project is developed and tested in Google Colab.

---

## Features

* Loads and preprocesses the MNIST dataset.
* Implements a Convolutional Neural Network (CNN) using TensorFlow/Keras.
* Trains the model on 60,000 images and tests on 10,000 images.
* Achieves around 98% accuracy on test data.
* Includes visualization of training history (accuracy and loss curves).
* Provides prediction examples with true vs. predicted labels.

---

## Project Structure

* `notebook.ipynb`: Colab notebook with complete code and explanations.
* `README.md`: Project documentation.

---

## Requirements

* Python 3.7 or higher
* TensorFlow 2.x
* NumPy
* Matplotlib

If running in Google Colab, these dependencies are pre-installed.

---

## How to Run

1. Clone this repository:

   ```bash
   git clone https://github.com/USERNAME/REPO_NAME.git
   cd REPO_NAME
   ```

2. Open the notebook in Google Colab or Jupyter:

   ```bash
   jupyter notebook notebook.ipynb
   ```

3. Run all cells to train the model and view results.

---

## Results

* Test Accuracy: \~98%
* Example predictions are shown with the actual digit label and model output.
* Training history plots illustrate the accuracy and loss during training.

---

## Future Improvements

* Add a user interface for drawing digits and testing the model.
* Experiment with deeper or different neural network architectures.
* Try transfer learning with other handwriting datasets.

---
