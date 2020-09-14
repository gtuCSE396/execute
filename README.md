# EXETUCION FOR OCTO-BOUNCER
## For Windows Machine
1. Create a mobile hotspot in your machine (username and password must be this: username:octobouncer psswd: octobouncer123)
2. Download "Desktop 5.1 build.rar" and exract
3. Run "OctoBouncer Desktop.exe"
4. Install mobile 4.2 Build.apk
5. Run mobile 4.2 Build.apk (Enter your host machine ip address and port. Port must be 7000. Exp: Ip Address: 192.168.137.1 Port:7000)
   NOTE: Must be on the same network with the host machine.
6. Run Raspberry pi via VNC Server Application. (You can see Raspberry Pi IP address with click Mobile Hotspot setting)
7. Open the raspberry terminal and enter this command : "python3 /home/pi/Embedded/final_project_socket.py
8. Now You are ready to send command via Desktop Application.

## For Linux Machine
1. Create a mobile hotspot in your machine (username and password must be this: username:octobouncer psswd: octobouncer123)
2. Download "DesktopLinux46Final.zip" and exract
3. Go to DesktopLinux46Final and use $chmod +x Desktop_4.26_Build_Linux.x86_64
4. run $sudo ./Desktop_4.26_Build_Linux.x86_64 
5. Install mobile 4.2 Build.apk
   NOTE: Must be on the same network with the host machine.
6. Run mobile 4.2 Build.apk (Enter your host machine ip address and port. Port must be 7000. Exp: Ip Address: 192.168.137.1 Port:7000)
7. Run Raspberry pi via VNC Server (You can see Raspberry Pi IP address with click Mobile Hotspot setting)
8. Open the  raspberry terminal and enter this command : "python3 /home/pi/Embedded/final_project_socket.py
8. Now You are ready to send command via Desktop Application.
