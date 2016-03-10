# port forwarding

In order to use the web server truly as a remote web server, we have to make it accessible outside the LAN. This can be achieved via port forwarding.

Configure the router to forward ports. If an external client sends a request over a particular port of the router, the router can pass it along to different IP addresses.

An excellent article can be found [here](http://www.howtogeek.com/66214/how-to-forward-ports-on-your-router/)

Suppose office ip address is `2601:641:101:1800:cc28:72aa:64:a454` 

The comcast business router default values are
http://10.1.10.1/
user: cusadmin
password: highspeed
![port forwarding](prot-forward.JPG)
Here the server IP address is the address of the computer inside the LAN running HTTP Server