## Networking room.........
osi(open sysytem interconnection)
### 1.physical layer:
like a road where cars (data) travel. It's just the medium that lets information move from one place to another, like cables or wireless signals.
## 2. Data link layer 
is like traffic rules on that road. It defines how cars (data) should move, when they can go, and how they avoid crashes. This ensures smooth communication between devices on the same network.
## 3.network layer:
like a GPS for the internet. It helps data find the best way to travel between different networks, just like a GPS finds the best route between cities.

## 4. Transportr layer 
 makes sure thatr the data reach the distination end to end comunication (Tcp , UDP)
 For example, when you load a website, your browser uses TCP to ensure all the web page data is received properly. But when you watch a live stream or play an online game, UDP is often used because speed is more important than perfect delivery.

## 5. session layer
establishing, maintaining, and synchronising communication between applications running on different hosts. 
1. establshing : Before two devices start communicating, the session layer helps them agree on the rules of the conversation.
It ensures both sides understand how long the session will last and how data will be exchanged.

2 . Session Maintenance (Synchronization):
   keeps track of communication, ensuring data is transmitted in the correct order.
   
   
If the connection is interrupted, the session layer can help resume from the last successful point instead of starting over.
Example: When downloading a file, if the connection drops, the session layer can help restart the download from where it stopped instead of starting from scratch.

3. session termination: when the connection is over the session layer ensure that the coneection is closed and free up system resources
### session protocols
1. NFS : (network file system) allow user to acces files in a remote computer as if they are stored locally.
   
3. sql session : when you connect to a database the session protocol ensure that the connection is active while quiers are being excuted.
   
3 . Remote Procedure Call (RPC) – Enables a program to request services from a program on another computer, making it seem like both programs are running on the same system.


## 6. presentaion layer

- The presentation layer ensures the data is delivered in a form the application layer can understand
- encoding and compression and data encryption

## IPV4
- conssist bof 4 octet 1 octet is from 0 - 255  iex we have 192.168.1.1 is a IPv4
- only the 0 aqnd 255 is for the network and broadcast address
- iex : 192.168.1.0 if for the network
- iex : 192.168.1.255 is for the braodcast address
- sending a to braodcast means sending to all hosts

### port numbers
- A port number is a unique identifier used to distinguish different types of network services running on a host (computer, server, or device)
  
-  just a numerical value assigned to a specific service or application running on a computer
  
- The port number is the apartment number (identifies a specific service or application inside the device).
  
- Port numbers are crucial for managing network communication and ensuring that data reaches the correct application on a device. Here’s why they matter:
   1. A web server might host a website while also offering secure remote access
   2. Firewalls use port numbers to allow or block specific traffic.
   3. the transport layer who use the port numbers to ensure that data is delivered to the destination
      
## telent 
- is a network protocol used to remotly access and control another computer.
- Telent is not secure as it send data in aplain text withput incryption.
- Testing if a specfiic port is open a server
- connecting a serever
- Sending mannual HTTP request

- What is the steps to connect to a webserver using telnet?
    - telnet (IP adress) 80
    - GET / HTTP/1.1
    -  Host: example.com

- Why would I do that?
   - Helps test if a web server is running.
   - Useful for debugging web requests.
   - Demonstrates how browsers fetch web pages behind the scenes.

























