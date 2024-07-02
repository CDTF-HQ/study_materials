# Chapter 1: Networking Fundamentals

# A. **Introduction to network technologies**

**A.1 Components of Computer Network :**

Clients (Endpoint) : devices that help us reaching and displaying data based on a request previously done (Laptops, Smartphones..)

Servers : Devices that hold a content for which clients make requests to seek it 

Peer to Peer connection : it's the operation of exchanging data between two clients

Local Resources : it's appliances we can use with no need of Network connections (HDD, SSD , Micro SD, RAM...)

Remote resources : same as local resources except that remote resources require network connection to reach it 

NIC (Network Interface Card ) :  it's the Appliance that gives us the possibility to connect network connectors (cables) like Ethernet cables into the slot () RJ45 -Registered Jack 45 or RJ11 for hardwire phones not IP's

Coaxial Cable NICs : different than Ethernet it's considered legacy but still in use for DVR or TV (the jack is called SMA Subminiature A connector ) 

Wi-Fi NICs : just like wired networks for wireless we find NICs that insure wireless connection between devices 

**A.2 Components of Infrastructure Network :**

these are the necessary equipment  that makes our Network Physically real

Switches : it's the equipment that insure connection between lot of hosts (clients and servers )

Router : is the Equipment that insure connection between LANs 

Firewalls : it's a segmentation way for the network either from inside or outside  it controls the flow of the network to make it more secure

- Traditional Firewalls : use a IP address + TCP/UDP port numbers Filtering
- Next-Gen Firewalls : came with more features like : deep packets inspection, it analyses packet to see if its corrupt or suspicious, App awareness it will filter traffic based on the content you're browsing, uses security services to insure a safe network experience ( like Cisco subscriptions for security services )
- IPS (Intrusion Prevention System) : generally it's built-in service inside next-gen firewalls and give it those features mentioned before
- Both of NGFW and NGIPS Are performing in-line protection, situated between a router and the Core Switches and Full Visibility of our Network environment

**A.3 Wi-Fi Components of a Network :** 

WAP (wireless access point ) : it's an appliance that gives hosts the possibility to wirelessly connect into a network and there's 2 sorts of it :

- Autonomous or standalone (need to be configured one by one
- Wi-Fi controllers that need a wireless LAN controller to control all its allocated access points has features like : covering a big number of WAPs at once, Security, Cloud or Appliance based config etc.. We can set those in many topologies : n+1 , n+n+1 etc.. (Backup concept)

Cisco DNA (Digital Network Architecture) Center : is a centralized management dashboard for absolute network control

- it has that great feature called intent based networking giving us the possibility to optimize a network depends on our needs
- GUI that let you design virtually your network, create topologies  maps and diagrams
- put on a golden IMG (the IOS version that will rule all the network appliances )
- control wireless profiles
