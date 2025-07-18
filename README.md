MNIST Image Classification with a Simple Neural Network
This project uses a simple neural network to classify handwritten digits from the MNIST dataset.

Dataset
Uses the MNIST dataset (60,000 training images, 10,000 testing images of handwritten digits 0-9, each 28x28 pixels).

Steps
Load and explore the MNIST dataset.
Preprocess data: one-hot encode labels, reshape images, and normalize pixel values.
Build a simple neural network model with two dense hidden layers and a softmax output layer.
Compile and train the model.
Evaluate the model's performance on the test set.
Visualize sample predictions.
Model Architecture
Input: 784 features (flattened image)
Hidden Layers: 2 x 128 neurons with ReLU activation
Output Layer: 10 neurons with softmax activation
Results
Achieved approximately 96.09% accuracy on the test dataset after 3 epochs.

How to Run the Notebook
Open in Google Colab and run all cells sequentially.

(Coursera help me to complete this project: https://www.coursera.org/learn/tensorflow-beginner-basic-image-classification)
