# in-browser-device-fingerprint

[Device fingerprinting](https://en.wikipedia.org/wiki/Device_fingerprint) is the process of uniquely identifying a device using it's (possibly) unique combination of device attributes. This is often used for tracking of users, for example to differentiate user HTTP requests originating from a group of users sharing a single public IP address.  

This repo contains a simple javascript-only implementation of browser-based fingerprinting. 

[generate_fingerprint.js](generate_fingerprint.js) contains code that you can use directly in your own web application. 

Opening [see_my_fingerprint.html](see_my_fingerprint.html) in a web browser will show you your own fingerprint (and an explanation of it).
