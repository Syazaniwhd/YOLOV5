# YOLOV5
This is the first draft of Object tracking using yolov5


This version of yolov5 is not full proof and still possess gaps before being fully implemented.

Here are some of the gaps:
1) Only works for pre-recorded YouTube videos, real time video tracking not working yet.
2) Unable to work on a live camera yet.
3) Only able to detect 80 classes from the pretrained "coco.name" training set obtained from darknet. Unable to detect other object aside from the 80 classes


Steps to follow: 
1) Clone this repository into a folder named "YOLOV5". Alternatively can also clone from https://github.com/akash-agni/Real-Time-Object-Detection
2) Set up virtual environment in terminal or anaconda prompt --> conda create yolov5 python=3.9
3) Activate virtual environment --> conda activate yolov5
4) navigate to the path directory of the cloned "YOLOV5" in your terminal or anaconda prompt
5) Install the required dependancies --> pip intall -r requirements.txt
6) Open Object_Detection_Real_Time.py on any IDE such as VS Code and run the script.
7) In Object_Detection_Real_Time.py , you can change the link in line 106 to any youtube video you like to experiment
8) The output of the ;labelled video will be stored in the same folder and named "Labelled.video.avi"
