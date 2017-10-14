# CLOS L3 Topology using OpenConfig Datamodel across multiple Datacenter Switch Operation Systems

## Topology
[ show pic ]

## Switch Initialization

Before the playbooks in this project can be executed on the switches, each
switch needs a base configuration. This is typically done in the switch
provisioning steps.

Configure all switches with a management interface, following best practises as
documented for each product. Create an ``ansible`` user that uses SSH public key
authentication. Assign the ``ansible`` user the ability to make any
configuration on the device. SSH password authentication should be disabled.

### Cisco Nexus OS
_mgmt interface already in a vrf_
### Arista EOS
_how you make eos mgmt interface to be in a vrf_

### JunOS
_how to do isolate a junos mgmt interface on qfx10k?_

### Cumulus
_how do you enable the mgmt vrf feature in cumulus_?





