There are 3 Java files which can be used directly by inserting them in the
proper packages as mentioned on the top of the class and then adding the
classes to the floodlightdefault.properties file
1. MySimpleSwitch.java
It's a basic switch which works at the IP level instead of the Mac level.

2. MySimpleFirewall.java
This works at the IP level again and do not allow the ip's "10.0.0.2" to communicate with "10.0.0.3" using ping command in mininet.

3. MySimpleApp.java
Intrusion Detection app using floodlight controller. Right now allowing to pass all the data through controller and maintaining the count of packets sent through all the host.
Then using "HoltWintersTripleExponential" algorithm to predict the traffic for next 10 seconds.
