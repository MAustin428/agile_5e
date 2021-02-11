## Existing Solutions (v2/9/21)
This document outlines existing solutions to CrapMap technical problems. The goal is to get to testing as quickly and cheaply as possible, and improve iteratively from there.

Casing and collar attachment I suggest we buy/find a cheap but weatherproof dog collar attachment (invisible fence, behavior buzzer,etc) and hack together a test casing and attachment.

## Hardware and Costs ESP8266 dev board $4-$5/per chip (without shipping)

Raspberry Pi 4 (between $40 and $80, depends on RAM)

Accelerometer sensor (~5$)

## Software solution A Google Maps API solution for Raspberry Pi 3. https://www.pubnub.com/blog/raspberry-pi-gps-lte-google-maps-api/

There are plenty of Raspberry Pi GPS solutions, but I think this is the most practical to start with.

## Business solution/scope?

Customer's problem: They are busy. Maybe they work at home. They can't watch their dog all the time. When their dog takes a crap, hardware transmits "crap" condition to application, and marks it on map (Google Maps API). Separate list of craps that user can "Check off" as they pick it up. Of course, users can lie about this, but we don't care.

Pro functionality can report found craps, which could notify basic users of un-cleaned craps. This wouldn't really work at, say, a dog park though, where everyone's dog craps.

Two levels of usage:

Basic membership- buy the collar, get the application free. Customer has bought hardware, and the software comes with it. Option to upgrade to pro.
Get application from ios/android free: Other people who want to know where poop is at can download and use for free. Free marketing. Option to upgrade to pro.
Pro membership- Either (1) or (2) can upgrade to Pro. Additional functionality TBD.
Ways to grow and monetize: smart house/shopping integration, dog health, collars.

## Legal issues (patents, wireless technology, reuse of existing technology, registering a company, liability, etc.)? Many other things? LLC is no problem, just costs some money- see legalzoom, for example. Other questions TBD.

## References 

Main Build
https://www.adafruit.com/product/746?gclid=EAIaIQobChMI4eLCn5CN4QIVSL7ACh0UUADREAYYASABEgLOs_D_BwE

Bluetooth LE Sensor Nodes to Raspberry Pi WiFi Bridge https://learn.adafruit.com/bluetooth-le-broadcastnet-sensor-node-raspberry-pi-wifi-bridge

Raspberry Pi with Multiple Wireless Sensors https://www.raspberrypi.org/forums/viewtopic.php?f=37&t=209565&p=1335845&hilit=raspberry+pi+with+multiple+wireless+sensors#p1339041

ESP8266 Microcontroller http://esp8266.net/ for ESP8266 datasheet

NodeMcu (recommended dev kit from pi forums) http://www.nodemcu.com/index_en.html