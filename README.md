# Enterprise Service Bus

Forwards OpenEMRConnect messages on to (or towards) their destination.

# Description

This module may be deployed at any number of nodes in the network where messages need to be forwarded.
For example, messages may be sent over more than one local area network (LAN) segment. There may be a
system that is connected to two different LAN segments, and the messages need to pass on from one LAN
segment to the other. The ESB may be deployed on the machine that is connected to both LAN segments.
If properly configured, it will forward messages from one LAN segment onto the other.

# Getting Started

Configure the application and network addresses of the modules you wish to route messages to in the
configuration file (openrmrconnect.properties).

# Dependencies

OEC Library (oeclib)

# Installing

To be completed.

# Running

To be completed.

## License

This project is licensed under the Mozilla Public License.
 
