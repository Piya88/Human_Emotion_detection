# Human_Emotion_detection

In this project I have created Convolutional Neural Network model to detect human emotions using pre-trained model (EfficentNet V2M) and Opencv to detect human faces from video/image inputs using haarcascade classifier.

https://github.com/Piya88/Human_Emotion_detection/assets/137636789/399d726e-43df-49c0-ba9a-8acb82d5f8c7

# About Model:

I have created humman emotion detection model which will predict - 'Angry', 'disgusted', 'fearful', 'Happy','Neutral','Sad','Surprise' emotions of human.
For this I have used emotion detection kaggle dataset - https://www.kaggle.com/datasets/ananthu017/emotion-detection-fer to train CNN model.
For CNN model architecture I have used transfer learning model EfficientNet V2M. I have fine tuned model to get best accuracy on train, validation and test model.
I have saved model weights for future prediction using keras.


# Opencv library:
Opencv libracy is an open source computer vision library, whcich process input images & videos to detect object, faces or handwriting of human.
I have used opencv to detect faces of human from video input and test my human emotion detection model on detected faces.

# Haarcascade classifier:
Haarcascade classifier is machine learning based obect detection model proposed by paul viola and Michael jones.  Opencv provides pre-trained haarcascade classifier model which we can use to detect faces from videos and images.

