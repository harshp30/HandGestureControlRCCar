# Glove_RcCar

July 2020
 
Tutorial by: https://www.youtube.com/watch?v=RTJ33EWmTRI&list=LL&index=116 
 
Youtube Demonstration: https://youtu.be/Z1HGJux7lb4
 
Pictures Link: https://drive.google.com/drive/folders/1CbhJcEJ8EC9QL585qkeUlkf-86gesy5V?usp=sharing
 
This project consists of two portions, the car and the glove.
 
The car:
 
	The car consists of five main components. 
	The first component is a simple 9V battery to powers everything on the car.
	The second component is an Arduino nano controlling the inputs and the outputs.
	The third component is a dual motor driver (L298n) that takes in signals from the Arduino and in turn controls...
	The fourth component which are the two motors directly connected to the motor driver.
	The fifth and final component is the radio communicator (NRF24L01) which allows for communication between the second Arduino on the glove.
 
The glove:
 
	The glove consists of four main components:
	The first component is again a 9V battery powering everything on the glove.
	The second component is an Arduino nano which communicates with the other Arduino on the glove by using...
	the third component is another radio communicator (NRF24L01) which is directly linked with the one on the car.
	The fourth and final component is a gyroscope and accelerometer (MPU6050) which calculates my hands’ positioning and level in turn moving the car in a specific 	direction.
 
Cohesive Explanation:
 
	
	The MPU6050 calculates the position of my hand, this is sent to the Arduino which then sends it to the radio module on the glove. 
	This is wirelessly communicated with the radio module on the car. The Arduino on the car then takes those outputs and sends them to the dual motor driver.
	The motor driver then turns on each motor accordingly which moves the car in the proper direction.
	This is all achieved in a matter of milliseconds and is a great way to explore wireless communications with the Arduino.
 
 
Challenges:
 
Working with the radio communicators was very complicated at first, but eventually, I understood all the components and how it works.
Hardware was a pretty big challenge in this project, a lot of wiring was required and had to be kept clean and organized.
 
Lessons:
 
Working with a 2 part wireless system was new for me and I learned a lot and was impressed at how good, even relatively cheap, sensors are. 
There was a minimal delay and everything worked smoothly.
This is also the first project where I used a soldering iron. (MPU6050 sensor on the glove)
 
Possible Improvements:
 
I would mainly improve the glove because it was quite uncomfortable to wear for long periods of time. Maybe using smaller and better sensors would have worked better. However, I 
am still very satisfied with the final result.
I could have also soldered more points on the car itself to improve connection points.

