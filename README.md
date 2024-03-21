# E-ink Desk Display
![](images/Eink_Display.jpg)
I made this E-ink display for my computer desk setup as an Always On display to show me information such as the date, time, weather, HDMI settings, USB settings, and CPU/GPU/Memory temperature information.

You can see a demonstration of the E-ink Display on YouTube: [The E-ink Desk Accessory.](https://youtu.be/d9forDotXkI)

# Home Assistant Requirement
This E-ink display has ESPHome installed and retrieves all live data (timesync, weather, etc..) directly from the Home Assistant (HA) server. Only code for the E-ink display (ESPHome) has been provided. The following integrations/services were used on HA for their respective data: 
-  ESPHome (HA Integration)
-  OpenWeather (HA Integration)
-  Yahoo Finance (HACS Component)
-  Libre Hardware Monitor (Software on PC)
-  [My DIY Macropad](https://github.com/davidz-yt/desk-controller)

![](images/Home_Assistant_Server.jpg)
