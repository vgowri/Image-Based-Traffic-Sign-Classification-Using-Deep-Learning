Traffic-Sign-Classification-Using-Deep-Learning

1.Introduction

Traffic sign recognition is a crucial component of autonomous driving systems, ensuring road safety by enabling vehicles to recognize and respond to various traffic signs. This project leverages a Convolutional Neural Network (CNN) to classify traffic signs based on the German Traffic Sign Recognition Benchmark (GTSRB) dataset. The model achieved a high classification accuracy of 96.31% on the test dataset.

  
2.Dataset
The dataset used is the GTSRB (German Traffic Sign Recognition Benchmark). It contains images of 43 traffic sign categories with the following structure:

*Training Set: ~39,000 images

*Test Set: ~12,000 images

*Image Dimensions: Resized to 32×32 pixels for training.

3.Model Architecture
The CNN model consists of:

*Input Layer: Accepts 32×32×3 images.

*Convolutional Layers: Extracts spatial features.

*Pooling Layers: Reduces spatial dimensions.

*Fully Connected Layers: Classifies the features into one of 43 classes.

*Dropout Layer: Prevents overfitting.

4.Results

*Accuracy: 96.31% on the test dataset.

*Confusion Matrix: A detailed confusion matrix visualizes the model's performance across all 43 classes.

5.Conclusion
This project successfully demonstrates the application of deep learning for traffic sign recognition. With a test accuracy of 96.31%, the model shows promising results and can be integrated into real-world autonomous driving systems for reliable traffic sign detection and classification.
