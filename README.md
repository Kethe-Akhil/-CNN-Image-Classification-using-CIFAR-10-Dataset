# -CNN-Image-Classification-using-CIFAR-10-Dataset
This project demonstrates a Convolutional Neural Network (CNN) built using TensorFlow/Keras (or PyTorch, depending on your code) to classify images from the CIFAR-10 dataset, a popular benchmark in computer vision.
The project uses the CIFAR-10 dataset, which consists of 60,000 32x32 color images in 10 classes, with 6,000 images per class:

Classes: airplane, automobile, bird, cat, deer, dog, frog, horse, ship, truck

Training images: 50,000

Test images: 10,000

The dataset is automatically downloaded from keras.datasets or torchvision.datasets when the code is executed.
🔍 Project Features
Image preprocessing & normalization

CNN architecture with Conv2D, MaxPooling, and Dense layers

Model compilation using categorical crossentropy and Adam optimizer

Training and validation accuracy tracking

Visualization of accuracy/loss curves

Model evaluation on test data

Class-wise prediction results
🛠️ Technologies Used
Python

TensorFlow / Keras (or PyTorch)

NumPy

Matplotlib

Seaborn
Achieved test accuracy of 70% after training for 25 epochs
