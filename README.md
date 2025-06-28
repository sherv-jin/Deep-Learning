Various types of gradient descent algorithm applied to CNN Architecture and its effect on training loss

Gradient Descent Algorithms in CNN for Image Classification
Objective
This project investigates the performance of various gradient descent optimization algorithms when applied to a Convolutional Neural Network (CNN) architecture for image classification tasks. The study focuses on analyzing how different optimizers affect the training loss dynamics and the model's convergence behavior.

Implemented Optimization Algorithms
The project includes implementations and comparisons of the following gradient descent variants:

Stochastic Gradient Descent (SGD)

Basic gradient descent with optional momentum

Simple but effective baseline for comparison

RMSprop

Adapts learning rates by dividing by root mean squared gradients

Good for non-stationary objectives

Nesterov Accelerated Gradient (NAG)

"Looks ahead" to adjust momentum more effectively

Often provides faster convergence than standard momentum

Adagrad

Adapts learning rates to parameters based on historical gradients

Performs well for sparse data

Adam (Adaptive Moment Estimation)

Combines ideas from RMSprop and momentum

Computes adaptive learning rates for each parameter

AdamW

Adam with decoupled weight decay regularization

Often provides better generalization than standard Adam
