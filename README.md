# Image Separation with U-Net 

A **Deep Learning** project developed in **Python** using **TensorFlow/Keras**, focused on separating an image into its two original components. To achieve this, a **U-Net architecture** was implemented and trained for the image separation task.
The repository contains the Jupyter Notebook with the implementation, training process, and results.

## 🎯 Task

Each input image is obtained by summing two images from different datasets:

* `img1`: **MNIST**
* `img2`: **Fashion-MNIST**

The **U-Net** receives the combined image as input and predicts the two original components.

## 🧠 Model

A **U-Net convolutional neural network** is used for this image-to-image reconstruction task. The model is trained to recover the spatial structure of both original images from their combined representation.

## 📊 Evaluation

The predictions are evaluated using the **Mean Squared Error (MSE)** between the predicted images and their corresponding ground-truth images.
