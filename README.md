# Emotion Detection
I created an emotion detection model trained on the fer2013 database from Kaggle. It is trained to detect seven emotions; anger, disguist, fear, happiness, sadness and neutral. I achieved achieved a 62.9 % test accuracy (the human accuracy for the fer2013 database is about 65%). I also created a notebook to preprocess any loaded images and identify emotion in them.

# Emotion Detection Part 1 Notebook
In this notebook I build the emotion detection model from scratch. First, I explored and preprocessed the data. Then, I created and trained a model on the data. I used transfer learning with the VGG16 model (already trained on the imagenet database). I then evaluated the model performance.

# Emotion Detection Part 2 Notebook
Here I explored the face_recognition library and used it to preprocess images. You can use this notebook by loading a model and an image. There are then functions that find faces in the model, scale them down, and feed them into the model, returning a prediction on all faces detected in the image.
