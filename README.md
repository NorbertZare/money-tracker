# money-tracker
This Robot Loves Money

I couldn't find a money tracker robot on the internet so I built one! :)
In this project I used a Raspberry Pi 3 B+ , two servo motors (SG90) , a Pi camera and a pan/tilt head. The operating system was Raspbian and I used OpenCV for image processing.

This robot basically tracks face picture on the money.(almost every money has a person's face on it.)
First based on a cascade file (money.xml) it can detect a face picture on the money. and after that it checks if the money is at the center of the frame or not.
If not, raspberry pi controls two servo motors to allow the Pi camera to pan/tilt while tracking the money in real time.

YouTube Video: https://youtu.be/tgW5lv0qEUE
