This is a FTP_Server example running on Network Dual Stack.
It allows you to manage files on SD Card from PC using FTP client.

Detailed description is available on:
www.keil.com/pack/doc/MW/Network/html/_f_t_p__server__example.html

Use this example to connect an evaluation board to a LAN with DHCP
server (most LANs have this). The example will configure the network
parameters automatically using a DHCP protocol.

If a DHCP server is not available, you may connect an evaluation
board to PC directly over a crosslink network cable. In this case
configure a PC to use a static IP address 192.168.0.1 and disable
a 'Dynamic Host Configuration' in Net_Config_ETH_#.h configuration file.
The default static IP address of this example is then 192.168.0.100

To test this example, open your FTP client and enter the
address ftp://stm32h7-eval/ or ftp://<boards IP address>

Default user    : admin
Default password: <none>
