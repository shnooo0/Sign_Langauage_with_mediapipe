# Sign_Langauage_with_mediapipe
A sign language interpreter using live video feed from the camera
 

Table of Content
- # info
- # demo
- # technologys and tools
- # setup
- # processes
- # features

# Info
- Realtime sign Language classification using Random Forest classification(RFC).
- 


![](https://github.com/shnooo0/Sign_Langauage_with_mediapipe/blob/main/image.png)



# demo
- Image gesture .
- ![](https://github.com/shnooo0/Sign_Langauage_with_mediapipe/blob/main/Img_gest.jpg)
===> test images 
- what are you doin?
![](https://github.com/shnooo0/Sign_Langauage_with_mediapipe/blob/main/what_are_you_doing.png)
- Really
![](https://github.com/shnooo0/Sign_Langauage_with_mediapipe/blob/main/Really.png)
- Expert
![](https://github.com/shnooo0/Sign_Langauage_with_mediapipe/blob/main/Wow%2CExpert.png)


# technologys and tools
- python
- open_cv
- scikit-learn
- mediapipe

# Setup 
- Use comand promt to setup environment by using requirment.txt
  ``` pyton -m pip -r requirements.txt```
- This will help you in installing all the libraries required for the project.

# Processes

=> if you want to run code in jupyter 
- open jupyter notebook and run file of ```test_all_project.ipynb```

=> if you want to run project in comand line
- open file path
- run code of ```collect_imgs.py``` to collect images from web camera
-  if you want use data set created by ourself go to [drive_Link](https://drive.google.com/drive/folders/14D0t8lCkxjpBVek3VM4L22YbwMm7Q0qL?usp=sharing) ., downoad data folder, extract folder and copy file to project file path
- to create data set run code of ```create_dataset.py```
- run code of ```train_classifier.py``` to train model
- to test model and read result run code of ```inference_classifier.py```


# Features
- Our model was able to predict the 20 text in the ASL with a prediction accuracy >90%.
- Incorporate feedback mechanism to make the model more robust
- Add more sign languages text


