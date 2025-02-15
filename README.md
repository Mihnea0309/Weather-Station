<h1>Weather Station</h1>

<h2>Objectives</h2>
This project was made to gauged a number of parameters, like the temperature, the humidity, the pressure and the UV index. This system has a LCD panel to show this information and also to compare it with real time data from the OpenWeather website. Also, the station is sending real time information towards two website, WeatherUnderground where I created my own station and sends its information to their site and ThingSpeak where I compare the station's information and the data from OpeanWeather. 
<br />

<h2>The description of the solution</h2>
I made the weather station using accessible components, such as:

- Data sensors: a DHT22 sensor for temperature and humidity, a UV sensor and a BME280 sensor for pressure
- Information Panel: a TFT LCD panel to display the necessary information
- Control unit: a Wifi NodeMCU V3, ESP8266, programmed to process the data from the sensors, to display it to the LCD Panel, to get the data and to send it to the mentioned websites
- Three 1.5V AA batteries to power the control unit
- The support: an improvisation made out of a phone case.
  
<h2>Project realization:</h2>

- First, I connected the data sensors and the control unit to make sure that everything is working as intended.
- Then, I connected the LCD Panel to display the information to the person using it.
- I then worked on the desired code for the control unit. I managed the data that was received, sent it to the websites and displayed it on the panel
- Lastly, after the coding was done, I connected the control unit to the 1.5V batteries for it to work remotely and without the need of a USB cable.
  
<h2>Testing the solution</h2>
To test the project, I performed the following steps:
- I loaded the code on the NodeMCU board.
- Once loaded, the panel displayed the wanted information, both from my data sensors and from the OpenWeather website.
- Then, I checked the data from the sensors using a thermostat (as I tested the station in a room while the OpenWeather data is from outside) and made sure that the data was also sent to the two websites that I wanted.
<p align="center">
  <img src="https://imgur.com/FzCbyC0.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p align="center">
  <img src="https://imgur.com/1oFxHwP.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<h2>Languages Used</h2>

- <b>C</b> 

<h2>Environments Used </h2>

- <b>Arduino IDE</b>

<h3><a href = "https://video-mea.s3.eu-north-1.amazonaws.com/Videoclip+proiect.mp4">Video of the Solar Tracker explained in romanian</a></h3>
<h3><a href = "https://video-mea.s3.eu-north-1.amazonaws.com/Videoclip%20proiect%20subtitrat.mp4">Video of the Solar Tracker explained with subtitles in english.</a></h3>




<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
