# esphome-configs
This is a collection of ESPHome configs I use for Home Assistant etc.   

I am converting to a new naming convention for these files.   

.base-wifi.yaml has the wifi config info
.base-web_server.yaml has the default web server config 
.device-sonoff_s31.yaml - This is the main device config for the Sonoff S31 Device.

The devices like s31-desktop-ups.yaml will include the sections needed.  

The Attic nodes are custom temp/humidity devices.


Moved to using the new package handler.   This allowed me to move a set of standard sensors for Home Assistant toe .base-uptime=sensors.yaml as well as a number of other things.


