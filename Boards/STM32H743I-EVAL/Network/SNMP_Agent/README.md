This program is a SNMP_Agent example example running on MDK Middleware Network.
It shows how to use a Simple Network Management Protocol to control the embedded system.

Use this example to connect an evaluation board to a LAN with DHCP
server (most LANs have this). This example will configure the network
parameters automatically using a DHCP protocol.

If a DHCP server is not available, you may connect an evaluation
board to PC directly over a crosslink network cable. In this case
configure a PC to use a static IP address 192.168.0.1 and disable
a 'Dynamic Host Configuration' in Net_Config_ETH_#.h configuration file.
The default static IP address of this example is then 192.168.0.100

To test this example, run windows application 'SNMPTest.exe' on your PC.
Enter the IP address of your embedded SNMP_Agent and click on 'Connect'.
When connected, you can change the LCD text on the target, control the
onboard LED diodes and monitor the state of onboard pushbuttons.
