GIT
===
https://github.com/kamorin/DHCPig

YOUTUBE
========
https://www.youtube.com/watch?v=hDmBF8PSTCU

DHCP PAckage
============
<img width="714" alt="DHCP-SHEMA" src="https://user-images.githubusercontent.com/12000025/66823412-e16cc400-ef4e-11e9-8534-8a8e9fe805a8.png">

DHCPDiscover Message
====================
DHCP client sends a DHCP Discover broadcast on the network for finding a DHCP server. If there is no respond from a DHCP server, the client assigns itself an Automatic Private IPv4 address (APIPA).

DHCPOffer Message
==================
DHCP servers on a network that receive a DHCP Discover message respond with a DHCP Offer message, which offers the client an IPv4 address lease.

DHCPRequest Message
===================
Clients accept the first offer received by broadcasting a DHCP Request message for the offered IPv4 address.

DHCPAcknowledgment Message
==========================
The server accepts the request by sending the client a DHCP Acknowledgment message.

DHCPNak Message
===============
If the IPv4 address requested by the DHCP client cannot be used (another device may be using this IPv4 address), the DHCP server responds with a DHCPNak (Negative Acknowledgment) packet. After this, the client must begin the DHCP lease process again.

DHCPDecline Message
===================
If the DHCP client determines the offered TCP/IP configuration parameters are invalid, it sends a DHCPDecline packet to the server. After this, the client must begin the DHCP lease process again.

DHCPRelease Message
===================
A DHCP client sends a DHCPRelease packet to the server to release the IPv4 address and cancel any remaining lease.

DHCPInform Message
==================
DHCPInform is a new DHCP message type, defined in RFC 2131. DHCPInform is used by DHCP clients to obtain DHCP options
