# CISCO PTTA 1.1.6 Assessment
## Overview
### Objectives
- Investigate Devices in a Wiring Closet
- Connect End Devices to Networking Devices
- Install a Backup Router
- Configure a Hostname
### Scenario
Most of the devices in the Seward Branch Office and Warrenton data center are already deployed and configured. We need to review the devices and networks deployed.
### Tool/s Used
- Cisco Packet Tracer
## Question & Steps
### Section 1
1. In Physical Mode, what are the cities connected?
   <br>
   Answer: Seward and Warrenton are the cities that connected by Submarine Cable<br>
   <img width="897" height="779" alt="image" src="https://github.com/user-attachments/assets/464aab4f-0d23-4c41-8b42-109a0ec21edf" /><br><br>
2. In Physical Mode, what is the name of the submarine cable?
   <br>
   Answer: Alaska United West (AU-West)<br>
   <img width="350" height="196" alt="image" src="https://github.com/user-attachments/assets/0b9dcf63-0047-4ffa-9a2d-5df2b185b046" /><br><br>
3. In Logical Mode, what are the wireless devices in the Teleworker Home?
   <br>
   Answer: Smartphone and Home_Laptop
   <br>
   Steps:
   - Go to Logical Mode
   - Look at the Teleworker Home subnet
   - The wireless devices is the devices that not connected with solid black line
   <br>
   <img width="569" height="363" alt="image" src="https://github.com/user-attachments/assets/66cc2cad-e1df-4c32-978e-aee52970c2b2" /><br><br>
4. In Physical Mode, what facility can you enter in the Seward, Alaska location?
   <br>
   Answer: Branch Office
   <br>
   Steps:
   - Go to Physical Mode
   - Click Seward City
   - Look the facilities in Seward
   <br>
   <img width="937" height="625" alt="image" src="https://github.com/user-attachments/assets/7e338aa1-c93a-4146-8d45-b1f7b1acf512" /><br><br>
5. Which Location can you enter in the other city?
   <br>
   Answer: Data Center and Teleworker
   <br>
   Steps:
   - Go to Physical Mode
   - Click Warenton City
   - Look at the location
   <br>
   <img width="1103" height="719" alt="image" src="https://github.com/user-attachments/assets/98f21d56-c504-488a-9623-d390563f6745" /><br><br>

### Section 2
1. Navigate to Branch Office in Seward
   <br>
   Steps:
   - Go to Seward<br>
   <img width="368" height="294" alt="image" src="https://github.com/user-attachments/assets/8c0f1bfe-9654-4ad1-9420-cdff27e3ae7c" /><br><br>
   - Click Branch Office<br>
   <img width="963" height="620" alt="image" src="https://github.com/user-attachments/assets/f8dad1b6-7ef8-44cb-9acf-ee0340bfa494" /><br><br>
   - Click Branch Office Wiring Closet<br>
   <img width="1010" height="657" alt="image" src="https://github.com/user-attachments/assets/e15209f2-2ad9-4c32-8dca-8b3f4a321e02" /><br>
   <img width="1136" height="802" alt="image" src="https://github.com/user-attachments/assets/d31c739a-29c5-4445-8dd4-20b15c7fa5aa" /><br><br>
2. Connect PC_1 FastEthernet0 to an empty FasrEthernet port on ALS2
   <br>
   Steps:
   - Select Copper Straight-Through Cable from Cable Pegboard<br>
   <img width="999" height="502" alt="image" src="https://github.com/user-attachments/assets/81de7d5e-efb1-4d41-a4b2-a98ba1e8df1b" /><br><br>
   - Connect to PC_1 FastEthernet0 port<br>
   <img width="701" height="279" alt="image" src="https://github.com/user-attachments/assets/d2f35e7b-6054-4894-a400-61c02fe621a5" /><br><br>
   - Connect the other side of cable to ALS2 FastEthernet port<br>
   <img width="965" height="152" alt="image" src="https://github.com/user-attachments/assets/8aadc9f1-43d9-47cd-b0a7-2ed3d73ff73e" /><br><br>

### Section 3
1. Connect RS232 port on PC_1 to the Console port on the Edge_Router
   <br>
   Steps:
   - Select Console Cable from Cable Pegboard<br>
   <img width="999" height="487" alt="image" src="https://github.com/user-attachments/assets/2bc1feea-355d-4e1a-a73c-08aa17f75407" /><br><br>
   - Connect to PC_1 RS232 port<br>
   <img width="286" height="109" alt="image" src="https://github.com/user-attachments/assets/078f2224-448d-4412-9c82-c2e6e2227c23" /><br><br>
   - Connect the other side of cable to the Edge-Router Console port<br>
   <img width="597" height="142" alt="image" src="https://github.com/user-attachments/assets/85b28dda-017b-4432-9efe-b1fc2ef19f58" /><br><br>

### Section 4
1. Install Backup_Router in the Rack and turn the power on
   <br>
   Steps:
   - Look at the Shelf side<br>
   <img width="467" height="626" alt="image" src="https://github.com/user-attachments/assets/6d30d7ac-bd7b-42c3-be64-a6c30f4f074a" /><br><br>
   - Put Backup_Router from Shelf to Rack<br>
   <img width="246" height="700" alt="image" src="https://github.com/user-attachments/assets/7ea04f7b-014c-4133-aa83-ceb7b71c9210" /><br><br>
   - Turn on the Backup_Router<br>
   <img width="958" height="108" alt="image" src="https://github.com/user-attachments/assets/c0c054d0-b02a-43a6-89e1-dee0dc3e8ca5" /><br><br>
2. Connect Laptop_1 to the Backup_Router with a USB cable
   <br>
   Steps:
   - Select USB cable from Cable Pegboard<br>
   <img width="1000" height="495" alt="image" src="https://github.com/user-attachments/assets/c8e3c502-e9d2-47de-9241-244273f09b08" /><br><br>
   - Connect to Laptop_1 USB port<br>
   <img width="486" height="418" alt="image" src="https://github.com/user-attachments/assets/cc9283ae-d4d0-410c-9f2d-0dfbd7259949" /><br><br>
   - Connect the other side of cable to the Backup_router USB Console port<br>
   <img width="947" height="101" alt="image" src="https://github.com/user-attachments/assets/05c6a502-6bff-45d5-922e-46f512d47873" /><br><br>

### Section 5
1. On Laptop_1, access the Desktop tab and click Terminal. The Terminal COnfiguration is already set with the necessary port configuration, and should be used with is default settings. Initiate the terminal connection.
   <br>
   Steps:
   - Go to Terminal on Laptop_1<br>
     <img width="1653" height="778" alt="image" src="https://github.com/user-attachments/assets/f70ebf94-c7bf-4f31-a8f2-5cfe96fe1d5f" /><br><br>
   - Use default configuration and click OK
     <img width="1649" height="273" alt="image" src="https://github.com/user-attachments/assets/fb4a9a33-1228-49c1-a067-efb43aa07900" /><br><br>
   - Eject initial configuration with `no` answer and press ENTER<br>
   <img width="582" height="227" alt="image" src="https://github.com/user-attachments/assets/9fae19fd-f6ea-4432-9f19-3f547da807fc" /><br><br>
   - Configure terminal and name the router Edge_Router_Backup<br>
   <img width="509" height="101" alt="image" src="https://github.com/user-attachments/assets/095f8629-d41c-4ef5-9dfb-fd9b0eaa8f2d" /><br><br>

### Section 6
1. Besides Ethernet and the console cables, what are other ways to connect devices?<br>
   Answer: USB Console cable
2. What is the difference between the wiring closet Rack, Table, and Shelf?<br>
   Answer:
   - Rack: To mount heavy devices such as router, server, PDU, etc
   - Table: To place end devices such as PC, Laptop, etc
   - Shelf: To place unused devices
3. How does Logical Mode differ from Physical Mode?<br>
   Answer:
   - Logical Mode: Provides view of network topology
   - Physical Mode: Provides view of the physical/hardware of the devices in the network
<br><br>

## Lessons Learned
- Understanding Workspace Differences: This activity teaches the critical difference between conceptualizing a network and physically building it. While Logical Mode allows to easily map out topologies using standard icons without worrying about real-world constraints, Physical Mode forces to think spatially. I've learned to manage equipment exactly as it exists in a corporate wiring closet, dealing with geographic locations, physical racks, and the actual distance between devices.
- Hardware and Power Management: A major takeaway is the hands-on management of hardware and power. Instead of devices magically turning on the moment they are placed, I`ve learned to visually inspect the front and rear chassis of enterprise equipment to locate power receptacles and physical toggle switches. I experience the realistic process of running AC power cables from switches and routers to a Power Distribution Unit (PDU), bridging the gap between theoretical configurations and the physical electricity required to boot up a device.
- Realistic Cabling Constraints: The lab also introduces realistic cabling constraints that network engineers face in the data center. I learn that I cannot just magically link devices together and I must visually identify and retrieve the correct cable type such as the light blue RS-232 cable for console management from a physical wall pegboard.
   





















