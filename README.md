# VMWare_Network


### Default Gateway in IP address

    A default gateway is an IP address that is specified in a device to enable it to communicate with other devices 
    that are not in the same network.Normally it is an address of the router interface that is connected to a network.
    The default gateway is always same as the IP address, the last byte or number is changed.

### SNAT - Source Network Address Translation

     A Secure Network Address Translation (SNAT) is an object that maps the source client IP address in a request to a 
     translation address defined on the BIG-IP device. A SNAT can be used by itself to pass traffic that is not destined 
     for a virtual server. It  allows traffic from a private network to go out to the internet. The gateway has one arm 
     on the public network and as part of SNAT, it replaces the source IP of the originating packet with its own public side IP.

          SNAT translates source IP addresses by replacing the IP address and port number of the internal network host to the
     external network address and port number of the device， thereby hiding the internal IP addresses or sharing the limited
     IP addresses.

### DNAT - Destination Network Address Translation

     Destination network address translation (DNAT) is a technique for transparently changing the destination IP address of an
     end route packet and performing the inverse function for any replies. Any router situated between two endpoints can perform
     this transformation of the packet.
     
         DNAT is used by an external host to initiate connection with a private network. So, it translates the public IP address 
     of an external host to the private IP of internal Host. DNAT can also translate destination port in TCP/UDP headers.

### ARP - Address Resolution Protocol

     Address Resolution Protocol is the Dynamic mapping technique used for mapping the logical address to a physical address, i.e.
     ARP accepts the logical address from the IP protocol and maps the address to the corresponding physical address and then pass
     it to the data link layer.
     
        ARP finds the hardware address, also known as Media Access Control (MAC) address, of a host from its known IP address. 
     ARP maintains a cache (table) in which MAC addresses are mapped to IP addresses.
