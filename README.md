# Lamport Clock Algorithm

The project, which implements the Lamport clock algorithm using Java RMI, aims to determine the order of events occurring in a distributed system.

The implementation was developed using Java RMI. On the server side, mathematical operations were created in order to be consumed by the clients. The server and clients have their own logical clock, internal events, and will send and receive messages. At all these events, the logical clock of each process (server or clients) will be calculated using the Lamport`s clock algorithm.

The system developed is based on a simple client server architecture where a client communicates with the server for any of the four operations from addition, subtraction, multiplication and division in a distributed system.
