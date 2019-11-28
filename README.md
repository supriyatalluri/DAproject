# DAproject
DA Project Group 14
Project Name : Diabetic Retinopathy Detection using ensemble of CNNs
Reference Paper : https://arxiv.org/pdf/1703.10757.pdf


To run code : 
Preprocessing: black.py --> clahe.py --> augmentation.py
Model: resnet50.py , inception.py , vgg16.py
Ensemble : ensemble.py
Predict : incpetion_predict.py , vgg16_predict.py , resnet50_predict.py


Dependencies & Installations:
Download dataset from https://www.kaggle.com/c/diabetic-retinopathy-detection/data  into a directory dataset
create two directories - clahe , black
Packages required:
tensorflow , pandas , numpy , skimage , cv2 , pillow , keras , sklearn , matplotlib
