# Drowsy-Driver-Prevention
Demonstrating the powerful life-saving potential of modern computer vision technology when applied to the ongoing problem of fatigued drivers drifting off to sleep at the wheel (causing an estimated 328,000 accidents annually), using just a USB webcam. Whilst my work serves primarily as a proof of concept of what can now be achieved at costs that significantly undercut anything presently available on the market that shares the same purpose, I do also go on to discuss methods in which this approach could be taken from prototype to fruition as a consumer-ready product. 


  
<p align="center">
  <img src="https://github.com/dr271/Drowsy-Driver-Prevention/blob/main/Readme%20Images/Figure%207.png">
</p>

<p align="center">
  <img src="https://github.com/dr271/Drowsy-Driver-Prevention/blob/main/Readme%20Images/Alarm%20Triggered.png">
</p>
  
The program functions by using a Histogram of Gradients (HOG) descriptors as feature inputs in to an SVM classifier for the purpose of facial recognition. A facial landmark predictor (courtesey of dlib) is then used to locate the eyes. A unique Eye Aspect Ratio (explained below) threshold is calculated for each user, and the alarm is sounded should the current EAR value falls below that of the threshold for more than a specified amount of time.


<p align="center">
  <img src="https://github.com/dr271/Drowsy-Driver-Prevention/blob/main/Readme%20Images/EARFormula.png">
</p>
  
<p align="center">
  <img src="https://github.com/dr271/Drowsy-Driver-Prevention/blob/main/Readme%20Images/EARoverTime.png">
</p>


This merely scratches the surface as a high-level overview of how it functions. Please see the writeup to look further in to any particular areas that may be of interest to you, as well as details on all references used.
