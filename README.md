# Transfer-Learning

Transfer learning is a machine learning technique that leverages knowledge gained from solving one problem and applies it to a different but related problem. It involves using a pre-trained model, typically trained on a large dataset, as a starting point for a new task.

In transfer learning, the idea is to transfer the learned knowledge, such as feature representations, from the pre-trained model to the new model. By doing so, the new model can benefit from the pre-existing knowledge and generalization capabilities of the pre-trained model, even when the new task has a smaller dataset.


Networks used: VGG16 , ResNet50, Inception V3 and Xception

# VGG16

VGG16 is a deep convolutional neural network architecture that was developed by the Visual Geometry Group (VGG) at the University of Oxford. It is known for its simplicity and uniform structure. VGG16 consists of 16 layers, including 13 convolutional layers and 3 fully connected layers. It has a fixed input size of 224x224 pixels and can classify images into 1,000 different categories. Despite its simplicity, VGG16 has achieved remarkable performance on various computer vision tasks, and its pre-trained weights are widely used in transfer learning.

# ResNet50

ResNet50, short for Residual Network 50, is a powerful deep convolutional neural network architecture that was introduced by Microsoft Research. It gained popularity by winning the ImageNet Large Scale Visual Recognition Challenge (ILSVRC) in 2015. ResNet50 is characterized by its use of residual connections, which enable the network to learn even deeper representations without suffering from the vanishing gradient problem. It consists of 50 layers and can classify images into 1,000 categories. The pre-trained weights of ResNet50 have been successfully applied in various computer vision tasks and are a popular choice for transfer learning

# Inception V3

Inception V3 is a convolutional neural network architecture developed by Google. It was designed to address the trade-off between computational efficiency and accuracy in deep networks. Inception V3 employs the concept of "Inception modules," which consist of multiple convolutional layers of different filter sizes to capture features at different scales. This architecture enables efficient use of computational resources while maintaining high accuracy. Inception V3 has been pre-trained on the ImageNet dataset and can classify images into 1,000 categories. It is widely used for transfer learning due to its efficiency and strong performance.

# Xception 

Xception is another convolutional neural network architecture developed by Google, which takes the concept of "Inception modules" to the extreme. It stands for "Extreme Inception" and focuses on improving the efficiency of feature extraction by using depth-wise separable convolutions. This technique reduces the number of parameters and computations required, resulting in a more efficient network. Xception has been trained on the ImageNet dataset and can classify images into 1,000 categories. Its pre-trained weights are often used in transfer learning to achieve state-of-the-art performance while minimizing computational resources.

