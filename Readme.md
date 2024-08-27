# MNIST Neural Network Interpretability
This project explores various neural network interpretability techniques applied to the MNIST dataset. It demonstrates the implementation and comparison of GradCAM, ScoreCAM, SmoothGrad, and Saliency methods to visualize and understand the decision-making process of a convolutional neural network (CNN) trained on handwritten digit recognition.
## Project Overview
The main objectives of this project are:
Train a CNN model on the MNIST dataset
Implement and apply multiple interpretability techniques
Visualize and compare the results of different methods
Provide insights into the model's decision-making process
## Technologies Used
Python,
PyTorch,
torchvision,
matplotlib,
numpy
## Model Architecture
The CNN model used in this project consists of:
1. Two convolutional layers
2. Two max pooling layers
3. Two fully connected layers
   
The model achieves an accuracy of approximately 98% on the MNIST test set.
## Interpretability Techniques
#### GradCAM (Gradient-weighted Class Activation Mapping)
GradCAM uses the gradients of the target class flowing into the final convolutional layer to produce a coarse localization map highlighting important regions for prediction.
#### ScoreCAM
ScoreCAM generates class activation maps by measuring the increase in prediction score when masked activations are forward-passed to the network.
#### SmoothGrad
SmoothGrad enhances gradient-based sensitivity maps by adding noise to the input and averaging the resulting sensitivity maps.
#### Saliency Maps
Saliency maps highlight the pixels in the input image that have the most significant impact on the model's prediction.
### Results and Visualization
The notebook includes visualizations for each interpretability technique, allowing for a side-by-side comparison of their effectiveness in highlighting relevant features for digit recognition.
### Usage
To run this project:
Clone the repository
Install the required dependencies
Open and run the Jupyter notebook Merck_Code_Final.ipynb
### Future Work
Potential areas for expansion and improvement:
Apply these techniques to more complex datasets and models
Implement additional interpretability methods
Quantitatively evaluate and compare the effectiveness of different techniques
### Contributing
Contributions to this project are welcome. Please feel free to submit a Pull Request.
