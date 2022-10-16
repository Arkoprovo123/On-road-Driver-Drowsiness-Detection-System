# Driver-Drowsiness-Detection
Driver drowsiness detection is a project built using Dlib and OpenCV with Python as a backend language.

<h3>Logic of project</h3>
The project includes direct working with the 68 facial landmark detector and also the face detector of the Dlib library. The 68 facial landmark detector is a robustly trained efficient detector which detects the points on the human face using which we determine whether the eyes are open or they are closed.


<h3>The working of the project</h3>
As you can see the above screenshot where the landmarks aredetected using the detector.
Now we are taking the ratio which is described as 'Sum of distances of vertical landmarks divided by twice the distance between horizontal landmarks'.
Now this ratio is totally dependent on your system which you may configure accordingly for the thresholds of sleeping, drowsy, active.