# Facial-Motion-Capture-System
This project is titled as “Facial Motion Capture System using Deep Learning”. The objective of this project is to develop Automatic Facial Motion Capture System which can take human facial images containing some expression as input and recognize and classify it into seven different expression class such as : Neutral, Angry, Disgust, Fear, Happy, Sadness, Surprise. This project uses machine-learning methods and computer vision to identify Facial Expression from the Input. First, we use a convolutional neural networks to classify human facial key points for each image. We then compare a number of classification algorithms thatuse certain features to predict the Emotion.
This project architecture shows the procedure followed for breed detectionusing machine learning, starting from input to final prediction.
![image](https://github.com/user-attachments/assets/416b3aaa-e5bf-451c-bf8b-c7517c4e619c)
![image](https://github.com/user-attachments/assets/39fa2dc6-76f3-49de-b469-a9de5b763a6b)

Description
Input Data: Input data is generally in .mp4 format or the camera source of the computer where the data is fetched and mapped in the data framed from the source columns. 
Importing Modules and Libraries: Libraries such as TensorFlow, KERAS, Flask etc. can be imported. 
Generating Training and Validation Batches: In this following step we are going to generate the Training and validation batches of dataset. 
CNN Model: 
Convolution: The term convolution refers to the mathematical combination of two functions to produce a third function. It merges two sets of information. In the case of a CNN, the convolution is performed on the input data with the use of a filter or kernel (these terms are used interchangeably) to then produce a feature map. 
Max – Pooling: Maximum pooling, or max pooling, is a pooling operation that calculates the maximum, or largest, value in each patch of each feature map. The results are down sampled or pooled feature maps that highlight the most present feature in the patch, not the average presence of the feature in the case of average pooling. 
Flattening: Flattening is converting the data into a 1-dimensional array for inputting it to the next layer. We flatten the output of the convolutional layers to create a single long feature vector. And it is connected to the final classification model, which is called a fully connected layer. 
Full Connection: Fully Connected Layer is simply, feed forward neural networks. Fully Connected Layers form the last few layers in the network. The input to the fully connected layer is the output from the final Pooling or Convolutional Layer, which is flattened and then fed into the fully connected layer. 
Training and Evaluating Model: Thus, created model is trained and evaluated to get the 
Output and the accuracy.
