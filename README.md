Custom and Pre-trained VGG16 and MLP Models for Image Classification
Image classification using pre-trained VGG16, custom VGG16, and MLP models with optimized hyperparameters and TensorBoard visualization.

📌 Project Overview
This project demonstrates:

Transfer Learning with a pre-trained VGG16 for efficient feature extraction.
Custom Architectures built for VGG16 and MLP, tailored to a specific image classification task.
Hyperparameter Optimization to improve model accuracy and efficiency.
🧠 Model Architectures
Pre-trained VGG16: Fine-tuned on a dataset using transfer learning. Includes 13 convolutional layers and 3 fully connected layers, based on ImageNet weights.
Custom VGG16: Similar to the original VGG16 but adjusted for the dataset, with modified fully connected layers.
Custom MLP: A fully connected model for lower-resolution (64x64) images, serving as a baseline model.
🛠️ Design Choices
VGG16: Chosen for its robust performance in image classification tasks.
MLP: Provides a comparison baseline to measure VGG16’s effectiveness.
Benefits of Pre-trained Models: Leverages learned features from large datasets, reducing training time.
⚙️ Hyperparameters
Learning Rate: 0.001 for balanced convergence.
Batch Size: 16 to optimize memory usage and training stability.
Epochs: Set to 10 for adequate learning without overfitting.
Hidden Layer Size (MLP): 128 neurons, selected for effective feature learning.