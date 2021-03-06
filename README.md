# centralized_P2P
1. **Objective**</br>
	This project aims to utilize the TCP/IP protocols to implement centralized peer-to-peer system, where there exists a central server that controls the file exchanging procedures.
	
2. **Introduction**</br>
	Peer-to-peer (p2p) system is a file exchanging system in the sense that every host in the peer network can download the files from other peers while sharing the files they have. Normal p2p system does not always rely on server. On the other hand, the centralized p2p relies on server to carry out the procedures between peers and peers. In this lab, the centralized scene is utilized. The server at this scene acts more like an information center in the sense that the peers will have to ask the server for the information about other peers instead of directly asking the peers. 
	
	Below is the basic concept of TCP connection:
	![Alt text](https://github.com/OscarLi9328/centralized_P2P/blob/master/concept.png?raw=true "Optional Title")
3. **System Description**</br>
	The system is divided into two parts: server, and client. As mentioned above, the server acts as a center that supports multiple connection. If a peer wants to download a file from other peers, it has to first connect to the server to get the information about the file. The client serves as an end-point for downloading. 
	The requests that the system supports are: register, listing, location, and leave, each side has its response to the request:
	![Alt text](https://github.com/OscarLi9328/centralized_P2P/blob/master/system%20description.png?raw=true "Optional Title")

Below is a figure that shows the concept of the operation on both sides.

![Alt text](https://github.com/OscarLi9328/centralized_P2P/blob/master/elaborate.png?raw=true "Optional Title")


