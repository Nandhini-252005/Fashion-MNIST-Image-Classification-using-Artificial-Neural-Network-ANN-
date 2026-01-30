# Fashion MNIST Image Classification using Artificial Neural Network (ANN)

This project focuses on classifying fashion product images from the Fashion MNIST dataset using an Artificial Neural Network (ANN) built with TensorFlow and Keras.

The project helps in understanding basic deep learning concepts such as data preprocessing, neural network design, and image classification.

---

## Dataset

**Fashion MNIST Dataset**
- 70,000 grayscale images
- Image size: 28×28 pixels
- 10 fashion categories:
  - T-shirt/top
  - Trouser
  - Pullover
  - Dress
  - Coat
  - Sandal
  - Shirt
  - Sneaker
  - Bag
  - Ankle boot
- 60,000 training images
- 10,000 testing images

---

## Model Architecture

The model used in this project is a **Fully Connected Artificial Neural Network (ANN)**.

### Architecture Details:
- **Input Layer:** Flatten layer (28×28 → 784 features)
- **Hidden Layer:** Dense layer with 128 neurons (ReLU activation)
- **Output Layer:** Dense layer with 10 neurons (Softmax activation)

```text
Flatten → Dense(128, ReLU) → Dense(10, Softmax)
