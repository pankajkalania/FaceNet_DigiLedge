# FaceNet_DigiLedge
This project is divided in five parts. 
1) Face Recognition
2) FaceNet Model
3) Load a FaceNet Model in Keras
4) Detect Faces for Face Recognition
5) Develop a Face Classification System

Face recognition is the general task of identifying and verifying people from photographs of their face. For this project we will be using FaceNet Model, which is a face recognition system that was described by Florian Schroff, et al. at Google in their 2015 paper titled “FaceNet: A Unified Embedding for Face Recognition and Clustering.”
It is a system that, given a picture of a face, will extract high-quality features from the face and predict a 128 element vector representation these features, called a face embedding.
The model is a deep convolutional neural network trained via a triplet loss function that encourages vectors for the same identity to become more similar (smaller distance), whereas vectors for different identities are expected to become less similar (larger distance). The focus on training a model to create embeddings directly (rather than extracting them from an intermediate layer of a model) was an important innovation in this work.

Download FaceNet model from https://drive.google.com/drive/folders/12aMYASGCKvDdkygSv1yQq8ns03AStDO_
Download dataset for this project from https://drive.google.com/open?id=16o4tpX2u4MQQegQR9mbE6Y6WJOOA661Z 
Put both "facenet_keras.h5" and dataset in your current working directory. 

Now we are ready to dive into our jupyter notebook, which is self explanatory. 
