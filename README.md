# L1L2-EthTester-v1.0

Testing ethernet cable integrity is one of the basic things, you just need cable tester. Tester is also used to determine where is failure cable's second end on the switch/router. For some reason, some employee "likes" to connect a few dollar device into a PoE switch or injector, the result is burnt tester. 
May introduce you my solution. This device has 2 RJ45 ports, one of them is simple NIC, the second - for cable testing wire-by-wire.
Tester has the ability to check if there is DHCP server on local network and if there is switch on the other side of the cable. If both yes - the result will be displayed as IP, subnet mask, gateway and DNS, if link is ON but no response form DHCP server - "DHCP 0" will be displayed. IP will be renewed automatically in a few seconds to check the connection again.
In wire test mode, it wokrs similarly as any other cable tester, compatible with remote part. If external voltage detected (enough to light up an optocoupler), the output is disabled, buzzer is screaming, display is in a bad mood. Removing hazardous cable from port will bring tester to a good mood. 

According to my colleagues, THIS is the device that should be sold in shops, it has both functions and "not afraid" of PoE (doesn't include connecting some 220V wires from outside). 
