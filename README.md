# Gradient Descent Optimisation in CNNs for Image Classification

A simple comparative study of gradient descent algos and their effects on training loss in CNNs for image classification tasks.

## Objectives
- Implement and analyse various gradient descent algorithms
- Evaluate their impact on training loss convergence
- Compare performance across standard image classification datasets

## Implemented Optimisers

| Optimiser       | Key Characteristics                          | Best For                      |
|-----------------|---------------------------------------------|------------------------------|
| **SGD**         | Vanilla gradient descent with momentum      | Baseline comparisons          |
| **RMSprop**     | Root Mean Square propagation                | Non-stationary objectives     |
| **Nesterov**    | Momentum with look-ahead correction         | Faster convergence            |
| **Adagrad**     | Parameter-specific learning rates           | Sparse data                   |
| **Adam**        | Adaptive Moment Estimation                  | General purpose               |
| **AdamW**       | Adam with decoupled weight decay            | Better generalization         |
