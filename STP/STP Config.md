**On each switch:**

enable

configure terminal

hostname SW1



**Check STP Status**

show spanning-tree



**STP automatically selects one switch as the Root Bridge. To control it manually:**

spanning-tree vlan 1 priority 4096



PS: Lower priority = higher chance to become root.



