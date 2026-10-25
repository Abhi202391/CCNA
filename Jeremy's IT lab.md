![alt text](image.png)
![alt text](image-1.png)

- One of the benefits of the layered systsem is that how the layers work together but remains separate

![alt text](image-2.png)
![alt text](image-3.png)

- PC1 wants to access the webapge hosted on the server 1
- There's problem: There are multiple process are running on server1: a web server process and file server process and possibly more. 
- So can PC1 ensure that its request reaches correct process on server 1 => That's the role of the trasnsport layer
- Each process on the server has associated transport port number
- Here a port is just a number to indentify the process running host

![alt text](image-4.png)
![alt text](image-5.png)
![alt text](image-6.png)
![alt text](image-7.png)
![alt text](image-8.png)

- Yes, a protocol can define how data is encrypted at the sender and decrypted at the receiver, but not every protocol does this.

A protocol is a set of rules that devices follow to communicate. These rules can define data formatting, transmission, error handling, authentication, encryption, and more.

![alt text](image-9.png)

How does a single message include all of this information at onece?

Let's see how these layer combine into stack and data moves through them using encapsulation and decapsulation 

- Encapsulation 
![alt text](image-10.png)

- Decapsulation 
![alt text](image-11.png)

![alt text](image-12.png)
![alt text](image-13.png)
![alt text](image-14.png)

- Same layer interaction 
![alt text](image-15.png)
![alt text](image-16.png)
![alt text](image-17.png)
![alt text](image-18.png)
![alt text](image-19.png)
![alt text](image-20.png)
![alt text](image-21.png)
![alt text](image-22.png)


