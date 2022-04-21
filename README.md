### Fault-detection-system
This project is done to be submited to sparks foundation as a Computer vision and IOT intern.
Fault detection is done using openCV library, First we read a folder of images as input for our program, then these images pass series of filters such as:
  1- Grayscale the image
  2- Threshold the grayscaled image
  3- Apply Erosion to enlarge the defects
  4- Inverse threshold the erosion output
  5- Apply canny edges filter to detect edges of the image
 After these filters we will have image with edges of the product and contours in the product if it has defects, we can simply find these contours by applying cv2.findContours()
 Finaly we display the result with the defects highlighted in red circle
