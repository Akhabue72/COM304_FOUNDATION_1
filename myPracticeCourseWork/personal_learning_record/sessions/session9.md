[Personal Learning Record](../../personal_learning_record/personal_learning_record.md) | [Session Notes](../sessions/README.md) 

# Session 9

## Topics covered
3/11/2025
* Networking

4/11/2025
* Networking cont(NAT)


## Personal Notes and research following this session
### Networking
* How computers and devices communicate with each other over the internet
* Modern computers use IP (internet protocol) to divide the data to be out into seperate "datagrams" or "packets" which contain a bunch of bytes.
* A **Internet Protocol** is the basic set of rules that gives every device and address, and ensures that data sent over the internet reaches the right destination
Analogy: Sending a Letter
* Data: The letter
* Packet: The envelope (a group of bytes put together into an envelope)
* IP: The rule that says "Every envelope must have a 'To' and 'from' written in a specific format"
* IP Address: The Street address on the envelope
* Computers in a network can be referred to as "hosts" or "servers" or "workstations"
* Computers can have several "ports" or "interfaces"
* A port is a number that helps direct internet traffic to the right place alongside the IP address
* While the IP can direct the letter to the street, the port tells it which apartment to go into
* Most computers will have at least a wifi interface and a wired one
* An **Endpoint** is literally one end of the communication point
* The final stop or starting point for communication on a network
* You make a phone call, the endpoints are you and the person you're calling's phones

### Structure
#### Router
* A router is the medium through which the data is sent to over internet (I think)
* It also sorts the data and makes sure it gets to the right place
* Offers a basic level of security

<img width="841" height="382" alt="image" src="https://github.com/user-attachments/assets/0b0019cd-a54b-4caf-a122-55d50241e435" />

#### NAT
* NAT is the process in which the router will swap the IP addresses and port numbers in the data packets as they travel to and from the internet, allowing all the divices in your home to share the single public IP address provided by your Internet Service Provider (ISP)
* Scrambles your IP for 2 reasons
  * Security
  * Saves Route
  * Theres a limited amount of IP addresses so it kinda makes more
* Essentially a firewall

<img width="828" height="419" alt="image" src="https://github.com/user-attachments/assets/f906e244-39a6-4b1a-a94f-18116d33eb80" />


### Research
* I was wondering why you would have multiple ports and the answer turned out to be fairly obvious: efficiency. By having multiple ports, your computer can recieve and process a bunch of information at once, leading to a more efficient transfer of data (multiple hoses, better water flow)
* The Switch is the device that lets all the devices at home talk to each other quickly without bothering the router. The "Router" I have at home is actally a combo device that has a router, a switch and a wifi access point
* The ISP (Internet service provider) cable is the physical connection that links the personal network to the global network
<img width="840" height="377" alt="image" src="https://github.com/user-attachments/assets/964a3e7e-4f4a-46a5-82fb-d780b9502d17" />


## Exercises and results
* Pinging random websites is interesting
* I was able to ping popular ones like roblox and google, but when I pinged more obscure ones (I wont say which 😄) I didn't get a response



## Summary of learning
The basic structure of the internet
