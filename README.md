## EXPT. NO. 1 SIMULATION OF STAR TOPOLOGY NETWORK
## AIM
To simulate a network with Topology, using Cisco Packet Tracer and to verify the connectivity between computer using ICMP.

## EQUIPMENTS REQUIRED
Desktop computer Cisco Packet Tracer 5.0 Software.

## PROCEDURE
STEP 1: Open a Packet Tracer Software.
STEP 2: Drag a 2950 Switch from tool bar and drop it in work area. STEP 3: Drag a PC Terminal from tool bar and drop it in work area. STEP 4: Repeat the Step:3 for four terminals.
STEP 5: Select Copper straight-through cable from tool bar and connect each PC Terminal with 2950 switch in different ports.
STEP 6: Click on the PC Terminal, Select the fast Ethernet Interface from configuration table and set IP address and Subnet mask.
STEP 7: Repeat the Step:6 for all the PC Terminals.
STEP 8: click on the PC Terminal and Select Terminal from the Desktop tab to verify the connectivity between the PC Terminals using Ping Command.
STEP 9: Select “add simple PDU” from tool bar and place it in source and destination PC Terminals to verify the connectivity

# IP CONNECTIVITY TABLE
| NAME | IP ADDRESS     | SUBNET MASK     | NETWORK      | CLASS   |
|------|----------------|-----------------|--------------|---------|
| PCO  | 192.168.1.10   | 255.255.255.0   | 192.168.1.1  | Class C |
| PC1  | 192.168.1.30   | 255.255.255.0   | 192.168.1.1  | Class C |
| PC2  | 192.168.1.20   | 255.255.255.0   | 192.168.1.1  | Class C |
| PC3  | 192.168.2.20   | 255.255.255.0   | 192.168.1.2  | Class C |
| PC4  | 192.168.2.30   | 255.255.255.0   | 192.168.1.2  | Class C |
| PC5  | 192.168.2.10   | 255.255.255.0   | 192.168.1.2  | Class C |


## NETWORK DIAGRAM
<img width="1280" height="720" alt="image" src="https://github.com/user-attachments/assets/d95394c9-3c44-42d1-b7a8-3a8d87229625" />
## OUTPUT
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/668bd4ca-51b5-4c84-9fe8-b9a7927b5ddf" />
## RESULT
Thus the computers in same network are able to communicate with each other and the communication between them were verified.
