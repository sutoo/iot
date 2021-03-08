As a summary, MQTT was designed to be suitable to support the following typical challenges in IoT, M2M, embedded, and mobile applications:

Be lightweight to make it possible to transmit high volumes of data without huge overheads Distribute minimal packets of data in huge volumes
Support an event-oriented paradigm with asynchronous bidirectional low latency push delivery of messages
Easily emit data from one client to many clients
Make it possible to listen for events whenever they happen (event-oriented architecture) Support always-connected and sometimes-connected models
Publish information over unreliable networks and provide reliable deliveries over fragile connections
Work very well with battery-powered devices or require low power consumption
Provide responsiveness to make it possible to achieve near real-time delivery of information Offer security and privacy for all the data
Be able to provide the necessary scalability to distribute data to hundreds of thousands of clients

A topic is a named logical channel



The MQTT server is the central hub of the publish/subscribe model we previously analyzed. The MQTT server is responsible of the authentication and authorization of the MQTT clients that will be able to become publishers and/or subscribers after they are authenticated and authorized.



```
Authentication 一般指身份验证，又称 “验证”、“鉴权”，是指通过一定的手段，完成对用户身份的确认。
Authorization 一般是授权、委托的意思，向… 授予职权或权力许可，批准等意思。
```
