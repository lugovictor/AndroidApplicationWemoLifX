# Android Application for WeMo and LifX Light Bulbs

This is a simple client application that can discover smart lights within our local network. Once the application is launched, it starts discovering all lights. Upon discovery, it displays the list of lights. From the list, we can perform several actions like power on/off, or make other changes based on what type of light we have discovered. For example, we can set different colors on the light if it is lifX. If there is multiple WeMo bulbs which belong to different WeMo switch(Bridge), we can discover and control each of them separately. 

## Getting Started

If the user wants to discover and control smart lights using this app, at first they will have to on-board the bulbs with the existing Android apps for WeMo and LifX. Here is how to do this:

* When the bulbs and WeMo switch are plugged in, they broadcast a wifi network. Find that network in Settings -> Wi-Fi and choose the Bulb network(WeMo/LifX).  
* Once we are connected to that wifi, we can try to add the bulb or device to the app. A window is shown with the available networks, choose your network and connect the bulb with it. The bulbs are now on-board. Details can be found in [LifX] (https://support.lifx.com/hc/en-us/categories/200238164-Getting-Started) and [WeMo] (http://www.belkin.com/us/support-article?articleNum=116173) sites.


## How it works?
* When the user clicks the "Find Lights" button, a broadcast is sent to the network for available devices. A list of available light bulbs are shown. If no device is found, an Intent is launched showing "No device found! like the image below:
![picture alt](https://photos.google.com/photo/AF1QipOAGZb6Z4TNNF_ZCFtPgU9CqtgwgUzmi-vfEgSy "Title is optional")

* It may happen that all the devices are not discovered in the first attempt. Therefore, we will have to press the back button and try again for discovery.

* If the connected lights are found on the network, those are displayed on the screen. From the list, we ca choose each of the bulbs and choose what we want to do.





