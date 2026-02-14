 Animal Image Classification using PyTorch : 

 Data source for this project is african-wildlife dataset available on kaggle(https://www.kaggle.com/datasets/biancaferreira/african-wildlife)

This project implements a Convolutional Neural Network (CNN) for multi-class animal image classification using the Animals10 dataset. The model is built and trained using PyTorch with GPU acceleration in Google Colab.

The dataset is organized using the ImageFolder format, where each class of animals is stored in a separate folder. The data is automatically split into training (80%) and validation (20%) sets to evaluate model performance. Images are resized to 128×128 pixels and converted into tensors before being fed into the model.

The CNN architecture consists of multiple convolutional layers followed by ReLU activation and max-pooling layers for feature extraction. Fully connected layers are used for classification. The model is trained using the Adam optimizer and CrossEntropyLoss function.

GPU support (CUDA) is enabled when available to accelerate training. During training, loss and accuracy are monitored across epochs to evaluate learning performance.

This project demonstrates the complete deep learning workflow, including data preprocessing, dataset splitting, model building, training, and evaluation. It provides a foundational understanding of image classification using convolutional neural networks in PyTorch.

Future improvements may include data augmentation, transfer learning with pretrained models (such as ResNet), model saving and loading, and visualization of performance metrics.
