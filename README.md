# Applied Machine Learning Assignment 1

## Task description

Train the Faster RCNN and small YoloV8 for object detection. 
Then evaluating them. 

### Steps 

1. Take photos of your environment of two or more objects. (at least 100 instances between all objects) 

2. Annotate them on roboflow. 

3. Train a Faster RCNN model using detectron2

4. Train Yolov4/5/6/7/8 (only one of them of choice) the smallest size

5. Evaluate both models based on mAP and speed and size.

## Solution

1. Firstly I took 105 photo of ```spoons``` and ```forks``` using my smartphone camera.

Example of the photo: 

<img src="screenshots/without_annotating.jpg" width="400" height="400" />

2. Using Roboflow I annotated them. 

After I used Augmentation:

 * 

<img src="screenshots/with_annotating.jpg" width="400" height="400" />
