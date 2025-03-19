# 2c.SIMULATING ARP /RARP PROTOCOLS
## AIM
To write a python program for simulating ARP protocols using TCP.
## ALGORITHM:
## Client:
1. Start the program
2. Using socket connection is established between client and server.
3. Get the IP address to be converted into MAC address.
4. Send this IP address to server.
5. Server returns the MAC address to client.
## Server:
1. Start the program
2. Accept the socket which is created by the client.
3. Server maintains the table in which IP and corresponding MAC addresses are
stored.
4. Read the IP address which is send by the client.
5. Map the IP address with its MAC address and return the MAC address to client.
P
## PROGRAM - ARP
![Screenshot 2025-03-19 110031](https://github.com/user-attachments/assets/ae09f8d1-b7dc-49b4-a2f8-1ffad0d92f16)

## OUPUT - ARP
![Screenshot 2025-03-19 111027](https://github.com/user-attachments/assets/39fc9978-71b7-42f2-ab65-51a65c7ede89)

## PROGRAM - RARP
![Screenshot 2025-03-19 111426](https://github.com/user-attachments/assets/8750e0eb-92eb-49b3-8b6e-eef159e8fc49)

## OUPUT -RARP
![Screenshot 2025-03-19 111943](https://github.com/user-attachments/assets/ab6eb5f2-c5ad-445a-9978-022052e0437e)

## RESULT
Thus, the python program for simulating ARP protocols using TCP was successfully 
executed.
