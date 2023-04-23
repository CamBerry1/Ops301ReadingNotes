## Why this topic relates to the module

***
## Questions / Prompts
### Layers of OSI Model
1. What does "OSI" stand for?
<br></br>Open Systems Interconnection<br></br>
2. List the 7 layers of the OSI model and what each one is responsible for
<br></br>
"All People Seem To Need Data Processing"
* Physical Layer: These are the physical cables and hardware needed for transmission. Also includes the electrical signal.
* Data Link Layer: Converts the electrical signals into 'frames'. 
* Network Layer: Gives directions to the data. Ie, where to send it
* Transport Layer: Ensures transmission integrity. Segments data to send in chunks.
* Session Layer: Manages the flow of data between 2 endpoints. Keeps track of the proper order of segments sent.
* Presentation Layer: Makes sure the data is in a format that we can understand.
* Application Layer: The user experience. This is the final product that is being send and recieved as percieved by humans.
<br></br>
3. Distinguish which layers are the “hardware layers”, and which layers are the “software layers”. What does that even mean?
<br></br>
Physical, Data Link, and Network layers are hardware. Transport, session, presentation, and application are software. The hardware layers are physical devices that create electrical signals as well as the mediums these electrical signals use to move. The software layers are the directions for these signals and the output.
<br></br>
4. How can the OSI model be used in troubleshooting?
<br></br><
Starting from the bottom up, we can see where the break in the chain is by following this model.
br></br>
### What is Wireshark and how is it used?
1. What is Wireshark?
<br></br>
A network packet capture tool. Used to dissect packets individually for inspection.
<br></br>
2. What is a packet?
<br></br>
A packet it a piece of data. Generally it is a small small part of a larger digital object, broken into a packet for easier transmission between 2 endpoints.
<br></br>
3. What 3 high-level things does Wireshark accomplish? How could these be used for nefarious purposes? For benevolent purposes?
<br></br>
Packet capture, filtering, visualization. Malevolently, we could use this to gain a wealth of information about a destination ip address. Benevolently, it can be used for microscopic troubleshooting.
<br></br>
***
## Things I want to know more about
* Punchdowns? Loopback Tests?
