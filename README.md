# OpticalFlow

This project implements the Optical Flow by tracking pre-initialized bounding boxes in a video. The objective is to track the movement of the object of interest as the video plays.

The project uses the KLT Tracking algorithm to calculate the Optical Flow.

It then does Similarity Transformation estimation between the tracked points in any two frames to calcualte the movement of the object of interest. 

### Input Scene ###
![Input scene](https://github.com/ayushgoel24/OpticalFlow/blob/master/input.gif)

### Output Scene ###
![Output scene](https://github.com/ayushgoel24/OpticalFlow/blob/master/result.gif)