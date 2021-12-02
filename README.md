# esx_taximeter

BEFORE
![alt text](https://i.imgur.com/1Q2ralm.jpg "ESX TaxiMeter")
AFTER
![alt text](https://media.discordapp.net/attachments/893214785930403881/893214955401256990/taximetre.png?width=1200&height=676 "ESX TaxiMeter")



ESX Taxi Meter is a plugin that adds a fare meter to your server. Great for those
who work as an Uber, Taxi, Limo, Tow, Aircraft Ferry or any other job that might
charge per mile of travel.

Right now it supports two types of fares. A "Flat Rate" fare which is simple
enough and a "distance" fare which shows a fare total based upon the distance
traveled. The driver is the "owner" of the meter and any passengers in the car
will be able to see the meter if it is active.

In the configuration file you can set restrictions on what vehicle and what ESX
jobs can use the meter. Currently supports both imperial and metric measurements.

The meter can be launched by using LEFTCTRL + G

# Requirements
ESX

# Installation
Run inside of your server-data/resources folder

AFTER REWORK


```
git clone https://github.com/michaelhodgejr/esx_taximeter.git [esx]/esx_taximeter
```

Add to your server.cfg file

```
start esx_taximeter
```

Create your config file from the default.

```
  cp config.default config.lua
```
# Known Issues
When a passenger gets in the vehicle, the driver will need to toggle the radar to
make it appear.

# Upgrading
