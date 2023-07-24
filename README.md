# Object Detection
Using tensorflow framework to build a deep learning model that will detect hand signs from web cam and surround it with a bounging box.

## Data Collection
The following train and test sets were created using OpenCV and labelImg.<br>
Train set:<br>
![Alt text](images/train.png?raw=true "Train set")<br>
Test set:<br>
![Alt text](images/test.png?raw=true "Train set")<br>

## Model Used
From Tensorflow Zoo, the pretrained ssd_mobilenet_v2_fpnlite_320x320_coco17 model is used. Installed using Tensorflow object detection API in Tenserflow Model Garden.

## Training and Testing
Model was trained using the default parameter and 2000 steps.<br>
![Alt text](images/trainr.png?raw=true "Train result")<br>
Loss graph in Tensorboard<br>
![Alt text](images/traing.png?raw=true "Train graph")<br>
Result on the test set.<br>
![Alt text](images/testr.png?raw=true "Test result")<br>
Expected Outout in Tensorboard<br>
![Alt text](images/testg.png?raw=true "Test graph")<br>

## Packages

## Future Scope
To make a web app that detects hand signs making webpage browsing interactive. 
