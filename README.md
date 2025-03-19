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
## PROGRAM - ARP
![Screenshot 2025-03-19 094551](https://github.com/user-attachments/assets/b8c7a5ed-68c2-435e-9802-8962b7da463d)

## OUPUT - ARP
![Screenshot 2025-03-19 095548](https://github.com/user-attachments/assets/5adf9d7d-d02a-4c02-a093-d4132d3b57ae)


## PROGRAM - RARP
![Screenshot 2025-03-19 100626](https://github.com/user-attachments/assets/98fb02a1-fdc6-48be-b686-b8c0d9c7d198)

## OUPUT -RARP
![Screenshot 2025-03-19 101441](https://github.com/user-attachments/assets/7f522d2f-3845-458a-8909-23c0d8ac3004)

## RESULT
Thus, the python program for simulating ARP protocols using TCP was successfully 
executed.
