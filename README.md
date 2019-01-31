SMART GARDENING AND IRRIGATION


When you hear the word Smart Garden, one of the things that pop up to your mind is the automatic measurement of the moisture content of the soil. 
If you're building a Smart Garden that waters plants automatically and give you the readings of the wetness of the soil, then you will definitely need a Soil Moisture Sensor.
A typical Soil Moisture Sensor consist of two components. A two legged Lead, that goes into the soil or anywhere else where water content has to be measured. 
This has two header pins which connect to an Amplifier/ A-D circuit which is in turn connected to the Arduino.

The Amplifier has a Vin, Gnd, Analog and Digital Data Pins. This means that you can get the values in both Analog and Digital forms.
Most soil moisture sensors are designed to estimate soil volumetric water content based on the dielectric constant (soil bulk permittivity) of the soil. 
The dielectric constant can be thought of as the soil's ability to transmit electricity. The dielectric constant of soil increases as the water content of the soil increases. This response is due to the fact that the dielectric constant of water is much larger than the other soil components, including air. 
Thus, measurement of the dielectric constant gives a predictable estimation of water content.
After verifying the code, upload it to the board and open the serial monitor. You will see the sensor data on the monitor being changed when you dip the sensor leads in water and when dry.
We use MQTT server ,which will help in remote access of the water sensor . Thus people with irrigation problems can be solved without them having to actually to come to the farm/land. when the humidity level goes down a certain limit the irrigation pump
switches on automatically or can give a prompt to user who is at a remote location and can be switched on by him too.
Using this technique ,water is saved hence promoting sustainable development and solving problems of transporttion. The humidity level is displayed to the person on his phone .The app on his phone
can be used to remotely switch on the ittigation pum,which will be switched off from the sensor signal when humidity increases a certain value.

