# Interfacing-Ultrasonic_sensor-Arduino

Automatic Room Lights System using Arduino is a very useful project as you need not worry about turning on and off the switches every time you want to turn on the lights. The main components of the Automatic Room Lights project are Arduino, PIR Sensor and the Relay Module.

Out of the three components, the PIR Sensor is the one in focus as it is the main device that helps in detecting humans and human motion.

In fact, the Automatic Room Lights project can be considered as one major application of the PIR Sensor. A similar concept is being already implemented in automatic toilet flush valves, hand dryers, etc.

![image](https://user-images.githubusercontent.com/70264806/113834287-4aca3d80-97a8-11eb-874d-2dce89b88948.png)

S = v * t
We have the value of t and we know that the speed of a sound wave is 340m/s. We have to convert the speed of sound into cm/us to calculate the distance. The speed of sound in cm/us is 0.034cm/us. The equation now will become ...

S = (0.034 * t)

We will divide this equation by 2 because we only require the distance it takes to hit the object and not the distance it takes to hit the object and come back. So, the final equation will be

S = (0.035 * t)/2

Here I am using Trigger pin at pin 12, echo pin at 13 and buzzer pin at 8 which will be the output. Here I have used, if the distance is less than 10, Buzzer pin will get high, that means buzzer will switch on for 500ms.
