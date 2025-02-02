# Day 16: Optimization Techniques

## What I Learned
- **Gradient Descent:** 
  - Understanding the basic optimization algorithm for minimizing loss functions.
  - Differences between Batch, Stochastic, and Mini-batch Gradient Descent.
- **Adam Optimizer:** 
  - Combines Momentum and RMSProp, adapting learning rates for each parameter.
  - Efficient and widely used for training deep learning models.
- **RMSProp:** 
  - Optimizes the learning rate based on recent gradient magnitudes.
  - Suitable for handling non-stationary objectives.

## Tasks Completed
1. **Data Loading and Preprocessing:** 
   - Loaded the MNIST dataset using TensorFlow/Keras.
   - Normalized pixel values and prepared data for model training.
2. **Model Implementation:** 
   - Built a simple neural network for digit classification.
3. **Optimization Experiments:** 
   - Trained the model using Gradient Descent, Adam, and RMSProp.
   - Compared performance metrics such as accuracy and loss.
4. **Visualization:** 
   - Plotted training loss and accuracy for different optimizers to analyze performance.

## Resources Used
- [Gradient Descent Explained](https://towardsdatascience.com/gradient-descent-algorithm-and-its-variants-10f652806a3)
- [Adam Optimizer Paper](https://arxiv.org/abs/1412.6980)
- [RMSProp Optimizer](https://www.cs.toronto.edu/~tijmen/csc321/slides/lecture_slides_lec6.pdf)
- [MNIST Dataset](http://yann.lecun.com/exdb/mnist/)
- [Keras Optimizers Documentation](https://www.tensorflow.org/api_docs/python/tf/keras/optimizers)
