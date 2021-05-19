# Advance-Gesture-Volume-Control-System


This project uses MediaPipe framework for Hand Landmark Detection that detects hand first and identify 14 landmarks on the hand. I have used specific landmarks to control volume using openCV and pycaw library of python to control the volume of system. 


<h3>Steps:</h3></br>

1.Create a Hand Detection Module that detects hand and identify 14 landmarks on the hand.</br>
2.Create  file that will call Hand Detection Module and identifies only those landmarks that are reponsible for our project.</br>
3.Use openCV to find the angle between desired landmarks and if the angle meets the desired correct posture angle that dumbbell curl count will be positive else throw an error "Incorrct Posture".</br>
4.One can use other set of landmarks to identify different exercises in correct posture respectively.</br>
