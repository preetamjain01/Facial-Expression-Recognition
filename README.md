Prerequisites
-------------
1. TensorFlow
2. Keras
3. tflearn

Dataset
-------
Since the dataset is large (287 MB), you can download it from this link, https://www.kaggle.com/c/challenges-in-representation-learning-facial-expression-recognition-challenge/data

Functionality
-------------
There are 3 functionalities in our application: 
1. Feed the image to the model and it gives you the appropriate expression (Code present in all the files) 
2. Feed a video to any of the models and it detects the expressions of the human faces in the video accordingly (Code present in all three models)
3. Detecting expressions in a live camera (Code present in all three models)

How to use?
-----------
- Download the dataset file fer2013.csv first from the above link and load or open it in your jupyter notebook
- We have provided the trained model, so you don't have to re-train the model
- Just load the model and run
- For VGG19 and ResNet, you have to build the architecture and then load the model to use it (till model.compile(), then model.save())
- Input a sample image, video in the model as mentioned above or use your webcam

Authors
-------
Rupesh Acharya, Preetam Jain
