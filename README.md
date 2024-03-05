# Handwritten Number Recognition
This project implements a handwritten number recognition model using Keras with the Sequential API. The model consists of two neural networks: one without a hidden layer and another with a hidden layer.

_Overview_
Handwritten digit recognition is a classic problem in the field of machine learning and computer vision. The goal of this project is to develop a model that accurately identifies handwritten digits from the MNIST dataset.

_Model Architecture_
Model 1: Without Hidden Layer
This model is a basic neural network with no hidden layers. It takes the input image of a handwritten digit and directly classifies it into one of the ten possible classes (digits 0-9).

Input Layer: Flatten layer to convert the input image into a 1D array.
Output Layer: Dense layer with softmax activation function for multiclass classification.
Model 2: With Hidden Layer
This model includes a hidden layer between the input and output layers. The purpose of the hidden layer is to introduce non-linearity and increase the model's capacity to learn complex patterns in the data.

Input Layer: Flatten layer to convert the input image into a 1D array.
Hidden Layer: Dense layer with ReLU activation function.
Output Layer: Dense layer with softmax activation function for multiclass classification.
Results
Model 1 (Without Hidden Layer):

# Accuracy: 92.4%
Although this model achieves decent accuracy, it lacks the capacity to capture complex patterns in the data due to the absence of a hidden layer.
Model 2 (With Hidden Layer):

# Accuracy: 98%
By adding a hidden layer, the model's accuracy significantly improves, reaching 98%. This demonstrates the importance of introducing non-linearity to capture intricate features in the handwritten digits.
Usage
Clone this repository.
Install the required dependencies (Keras, NumPy, etc.).
Run the script to train and evaluate the models.
Experiment with different hyperparameters, architectures, or datasets to further improve performance.

Conclusion
This project showcases the effectiveness of neural networks in recognizing handwritten digits. By comparing the performance of models with and without hidden layers, we observe the impact of model complexity on accuracy. The provided models can serve as a foundation for building more sophisticated handwritten digit recognition systems.





