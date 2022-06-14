# FHRP #

  A first hop redundancy protocol (FHRP) is a computer networking protocol which is designed to protect the default gateway used on a subnetwork by allowing two or more routers to provide backup for that address, in the event of failure of an active router, the backup router will take over the address, usually within a few seconds. In practice, such protocols can also be used to protect other services operating on a single IP address, not just routers.

Examples of such protocols include (in approximate order of creation):

- Hot Standby Router Protocol (HSRP) - Cisco's initial, proprietary standard developed in 1998
- Virtual Router Redundancy Protocol (VRRP) - an open (albeit patent encumbered) standard protocol
- Common Address Redundancy Protocol (CARP) - patent-free unencumbered alternative to Cisco's HSRP developed in October 2003
- Extreme Standby Router Protocol (ESRP) - Extreme Networks' proprietary standard with fast failover and also layer 2 protection
- Gateway Load Balancing Protocol (GLBP) - a more recent proprietary standard from Cisco that permits load balancing as well as redundancy
- Routed Split multi-link trunking (R-SMLT) - an Avaya redundancy protocol
- NetScreen Redundancy Protocol (NSRP) - a Juniper Networks proprietary router redundancy protocol providing load balancing
- Chassis Cluster Redundant Ethernet - a Juniper Networks proprietary Ethernet redundancy protocol, used on its SRX platform
- Multi-active Gateway Protocol (MAGP) - a Mellanox proprietary protocol based on VRRP that allows active-active operation
