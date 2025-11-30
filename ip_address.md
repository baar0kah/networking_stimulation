IP Addressing Scheme



Each VLAN uses a /24 subnet under the 10.10.x.0 addressing scheme.



| Department | VLAN | Network | Gateway |

|----------|------|--------|--------|

| Admin | 35 | 10.10.35.0/24 | 10.10.35.1 |

| Sales | 45 | 10.10.45.0/24 | 10.10.45.1 |

| IT | 55 | 10.10.55.0/24 | 10.10.55.1 |



Each end device was manually assigned an IP address within its VLAN subnet,

with the router subinterface acting as the default gateway.




