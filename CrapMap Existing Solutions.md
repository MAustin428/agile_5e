# Existing Solutions
This document outlines existing solutions to CrapMap technical problems. The goal is to get to testing as quickly and cheaply as possible, and improve iteratively from there.
##Hardware solution
https://www.adafruit.com/product/746?gclid=EAIaIQobChMI4eLCn5CN4QIVSL7ACh0UUADREAYYASABEgLOs_D_BwE

This links from site in software solution.

Casing and collar attachment
I suggest we buy/find a cheap but weatherproof dog collar attachment (invisible fence, behavior buzzer,etc) and hack together a test casing and attachment.

##Software solution
A Google Maps API solution for Raspberry Pi 3.
https://www.pubnub.com/blog/raspberry-pi-gps-lte-google-maps-api/

There are plenty of Raspberry Pi GPS solutions, but I think this is the most practical to start with.

##Business solution/scope? 

Customer's problem: They are busy. Maybe they work at home. They can't watch their dog all the time. When their dog takes a crap, hardware transmits "crap" condition to application, and 
marks it on map (Google Maps API). Separate list of craps that user can "Check off" as they pick it up. Of course, users can lie about this, but we don't care.

Pro functionality can report found craps, which could notify basic users of un-cleaned craps. This wouldn't really work at, say, a dog park though, where everyone's dog craps. 

Two levels of usage:
1. Basic membership- buy the collar, get the application free. Customer has bought hardware, and the software comes with it. Option to upgrade to pro.
2. Get application from ios/android free: Other people who want to know where poop is at can download and use for free. Free marketing. Option to upgrade to pro.
3. Pro membership- Either (1) or (2) can upgrade to Pro. Additional functionality TBD. 

Ways to grow and monetize: smart house/shopping integration, dog health, collars.

##Legal issues (patents, wireless technology, reuse of existing technology, registering a company, liability, etc.)? Many other things?
LLC is no problem, just costs some money- see legalzoom, for example.
Other questions TBD.