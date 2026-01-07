Title: Industrial Control System on Raspberry Pi (CODESYS)

Overview This project transforms a standard Raspberry Pi 5 into a PLC using the CODESYS Runtime. It demonstrates the bridge between IT (Linux) and OT (Industrial Control).

Features

Logic: Structured Text (ST) implementation of [Your Process, e.g., Tank Level Control].

HMI: Integrated WebVisu for real-time monitoring and control.

Connectivity: CODESYS CONTROL For RASPBERRYPi SL

Hardware Stack

Raspberry Pi 5 (16GB RAM)

OS: Raspberry Pi OS (Debian Bookworm)

Software Stack

CODESYS Development System V3.5

CODESYS Control for Raspberry Pi SL

How to Run

Open src/Sensor_Data.project in CODESYS V3.5. (Make Sure CODESYS for Pi SL is also Installed - You can use Condesys installer code install it)

Update the Gateway IP to match your Raspberry Pi.

Login and Download.

Access the HMI via browser at http://<YOUR_PI_IP>:8080/webvisu.htm.