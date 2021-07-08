## Computer Networking

> To achieve communication between computers on network , tasks are divided into 7 layers.

> Each layer follows a set of rules for sending/receiving data.

> Each layer builds on top of underlying layers, providing user services e,g, HTTP
 

### OSI layers

Below layers are used for end to end communication across networks
* application
* presentation
* session
* transport

Below layers are used for peer to peer communication between 2 nodes across a single hop

* network -> packets transmission/routing/internetworking/congestion control
* data link -> framing of packets/error, flow control between 2 nodes/channel access control /ARP
* physical


### TCP/IP MODEL

* Process/Application layer
* Host to Host Layer : end to end delivery using tcp/udp
* Internet layer : packetisation/send-receive packets over entire network
* Network access/link layer: combines data link layer/physical layer for communication between **2 devices on same network**


### macos network cmds

* networksetup -listallhardwareports - look for en0 in wireless or en1 in wired connection
