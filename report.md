## My approach:
1. Find the threshold for yellow color range:
    - adjust by experiment
    - Google it
    - my way: take samples from several video frames and take an average 
2. Use the threshold to filter out yellow pixels
3. Find contours
4. Filter out small contours 
5. Filter out not fully visible contours (if it touches a border)
6. Get the number of angles in the contour
7. Classify shape by amount of angles

## Challenges:
1. HSV color model format should be used, it is hard to find a range of yellow colors in RGB
2. It is easy to confuse RGB and BGR (still do not understand why BGR exists)