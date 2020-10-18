# Glove_RcCar

July 2020

Youtube Demonstration: https://youtu.be/Z1HGJux7lb4

Pictures Link: https://drive.google.com/drive/folders/1CbhJcEJ8EC9QL585qkeUlkf-86gesy5V?usp=sharing

This project consists on two potions. Portion one the car and the glove.

The car:

	The car consists of five main components. 
	The first component is a simple 9V battery to powe on everything on the car.
	The sceond component is a arduino nano controlling the inputs and the outouts.
	The third component is a dual motor driver (L298n) that takes in signals from the arduino and in turn controls...
	The fourth component which are the two motors directly connected to the motor driver.
	The fifth and final component is the radio communicator (NRF24L01) which allows for communication between the seconf arduino on the glove.

The glove:

	The glove consists of four main components:
	The first component is again a 9V battery powerign everything on the glove.
	The sceond component is a arduino nano which coommunicates with the other arduino o the glove by using...
	the third component which is another radio communicator (NRF24L01) which is directly linked with the one on the car.
	The fourth and final component is a gyroscope and accelerometer (MPU6050) which calculate my hands positioning and level in turn moving the car in a psecific direction.

Cohesive Explanation:

	
	The the MPU6050 calculates the position of my hand, this is sent to the aduino which then sends it to the radio module on the glove. 
	This is wirelessly communicated with the radio module on the car. The arduino on the car then takes those outputs and send it to the dual motor driver.
	The motor driver then turns on each motor accordingly which moves the cra in the proper direction.
	This is all achieved in a matter of milliseconds and is a great way to explore wireless communications with the arduino.


Challenges:

Working with the radio communiactors was very complicated at first, but eventually I understood all the components and how it works.
Hardware was a pretty big challenge in this project, a lot of wiring was requird and had to kept clean and organized.

Lessons:

Working with a 2 part wireless system was new for me and I learned a lot and was impressed at how good, even realitvely cheap, sensors are. 
There was a minimal delay and eveyrthing worked smoothly.
This is also the first project where I used a soldering iron. (MPU6050 sensor on glove)

Possible Improvements:

I would mainly improve the glove because it was quite uncomfortable to wear for long periods of time. Maybe using smaller and better sensors would have worked better. However, I 
am still very staisfied with the final result.
I could have also soldered more points on the car itself to improve connection points.
