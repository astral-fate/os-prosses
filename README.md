

Operating System Concepts

by Abraham Silberschat


Chapter Three: process 


Definitions, part 2 


Interprocess communication: is a mechnesim  that allows for exchanging, sending, and receiving data from each other 


Two kind of Interprocess communication 

- shared memory/ the region of the shared memory among the cooperative processes is established; hence process can exchange information by reading, and writing data to shared memory 

- message passing/ communication takes place by means of message exchanged between cooperating processes


Producer/ a process that produces information 


Consumer/ a process that consumer the information that the producer generates


Unbounded buffer/ a type of the buffer (bus system) that places no practical limit on the size of the buffer 


Bounded buffer/ assumes a fixed size of the buffer 


Direct communication/ 


Blocking, or synchronized, and unblocking and asynchronous/ it’s a methodology of communication between process, through a message that passes permeative such as send (), or receive() 


Rendezvous/ when the permeative send(), and receive() are blocking


Message/ the communication path that’s carried by the Mach operating system, which called the message 


Port/ the mailbox that reads and receives messages 


Port right/ the collection of the capabilities that’s necessary for ports to interact with each other. 


Bootstrap port: is an access that allows the tasks to the bootstrap port


Bootstrap trap/


Advanced local procedures (ALPC)/ the message passing facility in windows 


Connection ports, and communication paths/ are two types of port objects that winding uses to enable processes communication 


Section object/ a region of the shared memory that allows passing larger messages 


Pipe/ acts as a conduit for allowing two processes to communicate 


Write end/ on the process communication methods; producer-consumer fashion, is written on the end of the producer, by the help of the pipe


Read end/ the consumer processes reads from the end of the pipe


Anonymous pipe/ or ordinary pipes on windows, are termed as such


Two types of sockets:


Connection oriented/ that uses Socket classes in java


connectionless/ uses Datagram Sockets class


Loopback/ a mechanism that allows communication between client-server


Port/ a number included at the start of a message 


Stub/ a Service provides to the client side by the RPC system, to hide the details that allows for communication 


Marchal/ locates the port on the sever and marchals 5e parameters 


Microsoft interface definto language (MIDL)/ a stub code that compiled to define the interface between client-server 


Big endian/ store the significant byte first 


Small endian/ store the last significant byte


External data representation/ an independent mechanism representation to resolve the issues of representing data 


Match maker/ a rendezvous daemon, on fixes RPC ports


Binder/ a rich set of interprocess communication fashion provided to the android operating system 


Application components/ basic building block that provides utilities to android application 


Service/ one such application component 





