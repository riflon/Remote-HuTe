# Remote-HuTe #
DHT22 sensor with android app using classic UDP packets for reading temperature and humidity remotely.

## Idea ##
I spent some free time experimenting with Arduino. The idea was to implement a basic temperature & humidity station using the classic DHT22 sensor.
Going a bit further, I developed an Android application which uses UDP packets to communicate with the Arduino. Yeap! UDP packets are small and server implementation is simple. Ok!, so the client send a string chosen by the user as a key, and Arduino only responds if the key is correct (**THIS IS NOT A SERIOUS SECURITY MECHANISM, IT'S JUST SECURITY BY OBSCURITY AND IS FAR FAR AWAY FROM BEING SECURE. PLEASE KEEP IN MIND, THIS IS A SMALL ARDUINO PROJECT NOT AND INDUSTRIAL IMPLEMENTATION OF A REACTOR SENSOR**).


## Installation and Usage ##
Testing this project is really easy. You need to follow these steps:

1. Connect the prototype following the diagram. (more information --> https://www.hackster.io/riflon/dht22-remote-sensor-android-app-92402b).
2. Push the .ino project to the Arduino (remember to update key value to one of your choice).
3. Install Android application (with APK file, this is not a serious application so is not on the store).
4. On android application, enter the IP address of the Arduino, secret key value and remote port.
5. You should now view remote temperature and humidity on your device.
