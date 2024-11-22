# Traffic Sign Recognition using Deep Learning
In this project the computer recognizes the image that has been given to it. The ability to recognize a image by the computer was the main goal by this project. As we know that the computer does not understand images therefore these images are taken in the form of pixels or matrices. After this these images are fed into the neural network. The neural network are broken into layers .The first layer in the neural network is termed as input layer where the images from the dataset are taken. The second layers or the forth coming layers or the layers between are termed as hidden layers. The last layer is the output layer The output layer decides whether the input image entered from the dataset in correctly recognized by the machine or not.Pooling is same as convolution but no hyperparameters are there
unlike convolution. As there are so many classes or output labels SoftMax function is used. SoftMax function is a activation function used for multiclass classification.
Steps Overview
1. Data Preparation
Dataset: Images of traffic signs (43 classes).
Processing: Images resized to 30x30 pixels and normalized to [0, 1].
Train-Test Split: 80% training, 20% testing.

3. Model Architecture
A CNN model with:
Convolutional layers for feature extraction.
MaxPooling for dimensionality reduction.
Dropout for overfitting prevention.
Dense layers for final classification.
The model is compiled with categorical crossentropy loss and Adam optimizer.

4. Training and Evaluation
Training: The model is trained for 15 epochs with validation on the test set.
Evaluation: Accuracy is calculated using predictions on the test dataset.

Results include training/test accuracy, loss graphs, and predictions.
Results
Accuracy: The trained model achieves high accuracy on the test dataset.
Visualizations: Graphs of training/validation accuracy and loss.
