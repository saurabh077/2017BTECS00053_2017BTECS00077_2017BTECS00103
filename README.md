# 2017BTECS00053_2017BTECS00077_2017BTECS00103
DIP submission
Automatic Bottle filling inspection system using image processing

The application detects whether the bottle is filled properly or not.
The algorithm or the steps followed are :
1. Take the color sample of liquid and convert it to HSV
2. Set the lower And upper bounds of the Image
3. Input image for checking the filled level. Convert the  image to HSV representation
4. Mask the bits for the pixels which are in predefined range
5. Find the height of first few pixels from the top. Find out amount of bottle filled



Generally we can run it as follows
Open anaconda prompt
Command - python Level_detector.py
Enter color sample 
Write name of color sample
color_sample.png
Then it asks for the image which is to be processed
Enter input image
Image name will be entered say Bottle5.png then it would give an output.
