<h1>Smoke sensor</h1>
<p>The smoke sensor we have in the hackSpace is the MQ-2. This is a sensor that is not only sensitive to smoke, but also to flammable gas. The MQ-2 smoke sensor reports smoke by the voltage level that it outputs. The more smoke there is, the greater the voltage that it outputs. Conversely, the less smoke that it is exposed to, the less voltage it outputs.</p>

<p>These sorts of sensors are used in houses, large kitchens even Kingston University use them as they are very sensitive and accurate. This is due to a built-in potentiometer that adjusts the sensitivity to smoke. By adjusting the potentiometer, you can change how sensitive it is to smoke, so it’s a matter of calibrating it to adjust how much voltage it will put out in relation to the smoke it is exposed to.</p>

<p>The sensor only has 3 leads a VCC (5V), GND (GND) and (S) signal output pin that will be connected to an analogue pin. The Output pin gives out the voltage reading, which is proportional to the amount of smoke that the sensor is exposed to. Again, a high voltage output means the sensor is exposed to a lot of smoke. A low or 0 voltage output means the sensor is exposed to either little or no smoke. The example is a very simple smoke detector very similar to the ones we use in our houses. It will turn the alarm though the buzzer if the smoke level is too high. You can also measure the smoke level in the serial monitor.</p>
 
<p>This website has a guide and more information on the sensor...</p>
<link>https://www.waveshare.com/wiki/MQ-135_Gas_Sensor</link>

<p>The device has two signal pins, an AOUT (analogue) and DOUT (digital) choose one which best suits your project.</p>

<p>The device can be tested with a breath on the sensor dome, you will see a spike in the reading after a breath if the device is working and picking up indicated chemicals.</p>
