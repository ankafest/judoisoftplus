# judoisoftplus
## Version 1.0.0
## Intro
Homeassistant Integration for Judo I-soft Plus - Watersoftening System with leakprotection. The integration based on Rest-Api interface.

It's consists of 2 Parts:
* sensor for
    * waterhardness
    * waterconsumption
    * salt quantity 
    * status for possible actions

* button/slide switch for (possible actions)
    * leakprotection on/of
    * start waterregeneration 
    * watervalve on/off
    * change waterhardness 
    * Szenen

__The basis of solution is the rest-api, which you get if add ":8000" to the IP address of the Judo Isoft Plus water softening system in your web browser.__

# Connection
With this solution, only one device can be connected. The following information is needed for the connection:
![alt text](image-2.png)

__The remaining calls of the current Python version can't communicate with the completely outdated REST interface of the Judo-Isoft Plus water softening system because of TLS errors. The solution was to handle the communication through a reverse proxy.__

# Sensors and Button
![alt text](image.png)
![alt text](image-1.png)

# Disclaimer
This product is an open-source solution that was developed in our free time. Since we couldn't find any software online for the Judo Isoft Plus version — but urgently needed a solution — this software was programmed for private use. We're happy to share our solution with others this way, but we don't take any responsibility for any damage that might result from using the software.









