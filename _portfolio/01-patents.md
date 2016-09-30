---
layout: single
title: "Patents"
permalink: /portfolio/patents/
header:
    teaser: patents.png
---

--------------------------------------------

**[Patent Buddy
profile](http://www.patentbuddy.com/Inventor/Saravanan-Desikan/11542506)**

### Method and apparatus for server load balancing

[US 6980550 B1](https://www.google.com/patents/US6980550)

A method for forwarding data packets to one of a plurality of servers comprising
receiving a data packet from a source,  at a data packet forwarding device
having a plurality of ports,  performing a hashing function using a unique
component of the data packet as a seed value for the hash,  generating a hash
value using the hashing function,  looking up a table for an address of one of
the plurality of servers using the hashed value as an index to the table,  and
forwarding the data packet to a server corresponding to the address.

-----------------------------------------

### Method and system for multicast traffic reduction

[US 6977891 B1](https://www.google.com/patents/US6977891)

A method is provided to reduce multicast traffic by snooping IGMP control
packets on a packet-forwarding device. A multicast traffic reducer includes an
IGMP proxy,  which operates in conjunction with an IGMP snooper to intercept
selected IGMP control packets and generate proxy IGMP control packets in their
place. The IGMP proxy may include an IGMP query batcher to consolidate IGMP
queries to multicast host groups,  an IGMP query responder to consolidate host
responses to the IGMP queries to multicast host groups,  and/or an IGMP leave
forwarder to manage host IGMP leave packets. The IGMP proxy consolidates or
discards host-generated IGMP control packets and timely generates IGMP proxy
control packets in their place. The IGMP proxy further includes an IGMP layer-2
query generator to initiate IGMP queries for a layer-2 router multicast
application.

-----------------------------------------

### Methods,  systems,  and computer program products for dynamic network access device port and user device configuration for implementing device-based and user-based policies

[US 8775571 B2](https://www.google.com/patents/US8775571)

Methods,  systems,  and computer program products for dynamic network access
device port and user device configuration are disclosed. According to one
method,  when a user device is connected to a port of a network access device,
the type of user device is determined. The type of user device is used to locate
a corresponding port configuration policy. The port to which the device is
connected is dynamically configured based on the port configuration policy.

-----------------------------------------

### Methods and systems for associating and translating virtual local area network (VLAN) tags

[US 7558273 B1](https://www.google.com/patents/US7558273)

Methods and systems for associating and translating VLAN tags are disclosed. In
one implementation,  multiple different member VLAN tags are associated with a
translation VLAN tag. When a frame addressed to an unknown MAC address and
containing one of the member VLAN tags is received,  the frame is flooded to the
translation VLAN and to ports associated with the source member VLAN other than
the originating port. In the copy sent to the translation VLAN,  the VLAN tag is
replaced with the tag of the translation VLAN,  for tagged ports. For untagged
ports,  the input VLAN tag may simply be stripped from the frames. When a layer
2 frame addressed to an unknown MAC address and containing the translation VLAN
tag is received,  the layer 2 frame is flooded to each of the member VLANs and
to ports of the translation VLAN other than the originating port. The VLAN tag
in the frames forwarded to each of the member VLANs may be replaced with the
VLAN tag corresponding to each member VLAN,  for tagged ports. For untagged
ports,  the input VLAN tag may simply be stripped from the frames. MAC address
learning for frames received from member VLANs extends to the translation VLAN
but not to other member VLANs. MAC address learning for frames from the
translation VLAN extends to the member VLANs.
