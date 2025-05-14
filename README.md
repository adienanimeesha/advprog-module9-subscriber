1. What is amqp?
AMQP is an open, standardized way for applications to send and receive messages through a broker, such as RabbitMQ. This is so that producers and consumers don’t have to worry about the delivery, routing, or retries. Utilizing AMQP ensures the data packets get where they need to go reliably.


2. What does it mean? guest:guest@localhost:5672 , what is the first guest, and what is the second guest, and what is localhost:5672 is for? 
The first guest is the username. The second guest is the password. localhost:5672 tells the client to connect to the broker running on our own machine (localhost) at port 5672, which is the default AMQP port.