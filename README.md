# trafficmeter
Script for openwrt based routers that helps keep track of any unintended resets of the built-in traffic meter.

You will need to create directories on persistent storage(such as an attached USB stick) and make sure that they either match the script, or change the script to match what you can make. This applies to anything with the following directory path: /mnt/sda1/traffic_meter/

You might also need to change the two commands that grab the the values from the built-in traffic meter to match where your router stores the values. These are found at the begining of the script. 
currentread_u
currentread_d
