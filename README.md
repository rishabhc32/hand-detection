# hand-detection
Aim of the project is to move a robotic hand, mimicking humand hand based on a camera feed.</br>
The project is divided into
- Software
+ Hardware
## Software
We are using opencv to detect human hand and find the distance between palm center and finger tips. Popular method of convex hull and convexity defect is used to detect the movement of hand. 

Convex Hull and Convexity defects|
---|
![alt Convex Hull and Convexity defects](https://i.stack.imgur.com/EBlnT.png "Convex Hull and Convexity defects")|


![alt Human hand tracking](https://image.ibb.co/cOCEvm/screenshot.png "")
In the 'contours' windows the palm center in blue, red dots indicate convexity defects while the green boundary is convex hull. Knowing the coordinates of palm center and fingerips(convex hull points) we can find the amount by which each finger is closed, moving the robotic hand's finger in same proportion.
## Hardware
+ Todo
