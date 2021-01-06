# Drowsy-Driver-Prevention
Demonstrating the powerful life-saving potential of modern computer vision technology when applied to the ongoing problem of fatigued drivers drifting off to sleep at the wheel (causing an estimated 328,000 accidents annually), using just a USB webcam. Whilst my work serves primarily as a proof of concept of what can now be achieved at costs that significantly undercut anything presently available on the market that shares the same purpose, I do also go on to discuss methods in which this approach could be taken from prototype to fruition as a consumer-ready product. 


  
  ![Figure 7](https://user-images.githubusercontent.com/52629191/103778959-f2f62c00-502a-11eb-896a-ed06d7cabf8b.png)

<p align="center">
  <img src="https://github.com/dr271/Drowsy-Driver-Prevention/blob/main/Readme%20Images/Alarm%20Triggered.png">
</p>
  
The program functions using the calculated Eye Aspect Ration (EAR). A unique threshold is calculated for each user, and the alarm is sounded should the current EAR value falls below that threshold for more than a specified amount of time.


<p align="center">
  <img src="https://github.com/dr271/Drowsy-Driver-Prevention/blob/main/Readme%20Images/EARFormula.png">
  <img src="https://github.com/dr271/Drowsy-Driver-Prevention/blob/main/Readme%20Images/EARoverTime.png">
</p>


