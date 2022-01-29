# Detecting Motion and Mobile Objects in a Video

**GOAL:**

To detect motion and moving objects from a video using some libraries with Python.

**WHAT I HAVE DONE:**

Created a project for detecting motion and moving objects from a video.

Read the video of moving objects using openCV for getting the frames from the video to check the motion of objects.

- Applied the gaussian blurr on both the frames.

- Taken the absloute difference between the frames so that the cars that has moved are highlighted in grayish-white color.

- Created a threshold, it will give us total white color for those cars which are moving or in motion.

- Find these white pixels to detect motion by calculating the number of white pixels.

- Checking the condition if white pixels are more than 5% of total pixels in the frame, if pixels are detected then the object is in motion otherwise not.

- Filling the gaps in white pixels using dilation so that we can draw bounding boxes, now these are the counters and can be detected. 

- Find the counters then will draw the rectangles or bounding boxes to highlight the objects

And finally, displaying the frame or image in which the objects have moved from their positon.

**SCREENSHOTS:**

**1. Frame 1 from the Video**

![frame1](https://user-images.githubusercontent.com/60546202/151660094-b4b28fdc-28f2-4a1e-b563-c8aad9ecc8ed.png)


**2. Frame 2 from the Video**

![frame2](https://user-images.githubusercontent.com/60546202/151660099-17bebccf-123e-420c-8ee1-a99d523608a3.png)


**3. Output**

![final](https://user-images.githubusercontent.com/60546202/151660103-e6988545-f3ef-42f7-9c28-3ff7d1886c46.png)
