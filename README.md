# **Finding Lane Lines on the Road**
Self-Driving Car Engineer Nanodegree Program

---
## Project Details
When we drive, we use our eyes to decide where to go.  The lines on the road that show us where the lanes are act as our constant reference for where to steer the vehicle.  Naturally, one of the first things we would like to do in developing a self-driving car is to automatically detect lane lines using an algorithm.

The goal of this project is to make a pipeline that finds lane lines on the road. In the implementation we detect lane lines in images using Python and OpenCV.

<img src="docs/laneLines_thirdPass.jpg" width="480" alt="Combined Image" />


---
## Implementation Details
Below you will find a summary of the essential details about the repository, files, installation and required dependencies. The project contains various files essential to whole pipeline of the implementation:

* `P1.ipynb`: script used to create and train the model
* `video.mp4`: video of the car driving autonomously around the track for one full round
* `Additional videos`
    * YouTube


---
## Reflection

### Describe your pipeline. As part of the description, explain how you modified the draw_lines() function.
My pipeline consisted of 5 steps. First, I converted the images to grayscale, then I ....

In order to draw a single line on the left and right lanes, I modified the draw_lines() function by ...

If you'd like to include images to show how the pipeline works, here is how to include an image:

![alt text][image1]


### Identify potential shortcomings with your current pipeline
One potential shortcoming would be what would happen when ...

Another shortcoming could be ...


### Suggest possible improvements to your pipeline
A possible improvement would be to ...

Another potential improvement could be to ...


---
## Author

Simon Bøgh