# Gradient Descent Optimization in CNNs for Image Classification

A simple comparative study of gradient descent variants and their effects on training loss in convolutional neural networks for image classification tasks.

## Objectives
- Implement and analyze 6 gradient descent optimization algorithms
- Evaluate their impact on training loss convergence
- Compare performance across standard image classification datasets

## Implemented Optimizers

| Optimizer       | Key Characteristics                          | Best For                      |
|-----------------|---------------------------------------------|------------------------------|
| **SGD**         | Vanilla gradient descent with momentum      | Baseline comparisons          |
| **RMSprop**     | Root Mean Square propagation                | Non-stationary objectives     |
| **Nesterov**    | Momentum with look-ahead correction         | Faster convergence            |
| **Adagrad**     | Parameter-specific learning rates           | Sparse data                   |
| **Adam**        | Adaptive Moment Estimation                  | General purpose               |
| **AdamW**       | Adam with decoupled weight decay            | Better generalization         |
