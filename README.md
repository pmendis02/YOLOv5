This file explains how I trained my Object Detection Model.


The first step being setting up my Google Colab and connected my google drive to the Colab notebook. This allowed me to have access to my previous training files.
The next step was to upload the Ultralytics YOLOv5 open source repository to the Colab notebook. Now I have my data images along with their respective .txt bounding box files, the data.yaml file and all the YOLOv5 model files. 
Then I connected to the Colab GPU and then installed all the requirement packages for the YOLOv5 model.
The next step was to train the model using the imported YOLOv5 files. I set epocs to 50 however if set to 100 my accuracy would have improved.
I split my images into two folders, one for training and another for testing. 
