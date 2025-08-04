🖐️# **Hand Gesture Recognition** 

🔍 **Overview**:
To build a machine learning model that classifies hand gestures from grayscale images using Convolutional Neural Networks (CNNs). These gestures can be used for applications like human-computer interaction, sign language interpretation, and gesture-controlled interfaces.
The final system can be extended for real-time gesture detection using webcam input, making it a foundation for more interactive and intelligent systems.

 🧠**Model Architecture** (CNN):
* Used a Sequential CNN model with:
* Two convolutional layers with max pooling
* Flatten layer
* Dense (fully connected) layer with ReLU
* Dropout for regularization
* Final softmax output layer (10 classes)

  ✅ **Observations**:
The model was able to learn basic gesture patterns.
* Real-time prediction using webcam was functional.
* However, accuracy on test images was inconsistent due to:
* Varying lighting conditions
* Background noise
* Limited training data

  👤 **Author**
  Zahadana Haneef T
