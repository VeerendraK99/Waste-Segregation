# Waste-Segregation

This project automates the task of waste segregation in public dustbins by classifying waste as either plastic or not. We use a Raspberry Pi along with a servo motor, IR, Ultra-Sonic Sensor, Pi Cam and a server(laptop) to accomplish the project.

The project has been implemented as an IoT system which captures images through the Pi and sends it to a server for processing. On the server, we use CNNs for segregation of 
waste, which are used to identify type of waste that was dumped. The server communicates back to the Pi and the Pi actuates accordingly by turning
the servo motor and thus dumping the garbage to either the plastic or non-plastic side. We use an ultrasonic sensor to detect the level of garbage accumalated in the bin. Whenever
the level of bin crosses the predefined threshold a messege is sent to the recipients.
