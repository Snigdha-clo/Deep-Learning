Convolutional Neural Networks for Image Classification — CIFAR-10

Implementation and analysis of Convolutional Neural Networks using TensorFlow/Keras: convolution mechanics, stride/padding effects, feature map visualization, pooling comparison, and a full CNN classifier trained on CIFAR-10.

Objective

Understand the working principles of CNNs by implementing convolution, pooling, and feature map visualization, then build and evaluate an image classifier.

Key Takeaways
Larger kernels shrink the output feature map faster (fewer valid sliding positions).
Stride 2 halves spatial dimensions relative to stride 1; same padding preserves input size, valid padding shrinks it.
Weight sharing is what makes CNNs far more parameter-efficient than MLPs on image data.
Pooling reduces spatial dimensions and parameter count, and adds a degree of translation invariance.
Without regularization, deeper training epochs push training accuracy well past validation/test accuracy — a textbook overfitting signature.
