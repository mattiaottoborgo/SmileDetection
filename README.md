# Smile-Detection-DeepLearning
## For this project you need these packages: 
### Torch , CV2 , PIL , Numpy , OS , face_recognition

### Simple project to apply the concepts of fine tuning of pre existing model. The aim of the project is to implement a smile detector algorithm using pytorch. The training of the model is based on resnet34 pretrained.
![face](https://user-images.githubusercontent.com/41823988/66033776-d197bd80-e514-11e9-94d4-49c884606810.gif)

### https://drive.google.com/open?id=1qQgzHkYmKueY8tyh0f32EIq0Bohoyuvl

### main.py contains main code for train the dataset. The dataset contains cropped faces from a main dataset that have croped with face_detection.py code. The dataset have 3 classes: laugh, poker, and smile. Laugh and smile folders have about 900 images and poker folder has 373 images. Change your path for training the model. The resize.py is a code for resize all images in a folder and the facerecognition.py is a code for cropping faces from all images.
### After running the main.py you have a (my_resnet34_lr0.03_SGD_model.pth) file and you will use it in Predict-image.py code for predicting your images. The output of predict-image.py is like the picture below.

![Screenshot (26)](https://user-images.githubusercontent.com/41823988/66072569-244b9680-e562-11e9-860b-b59cd634d509.png)

### Enjoy Deep Learning!


