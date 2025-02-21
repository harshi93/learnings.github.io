# NAT Gateway V/s NAT-Instance
1. NAT-Gateways are AWS managed | NAT-Instances are customer managed
2. NAT-G/W Support scale up 100 GBPs | NAT-Instances Depends on underlying instance
3. NAT-G/W On timeout sends RST pkt to backend | NAT-Instances On timeout sends FIN pkt to backend
4. Port-forwarding not allowed on NAT-G/W |  port-forwarding can be configured on NAT-Instances
5. Fragmented pkt forwarding available only for UDP based pkts on G/w | fragmented pkt forwarding available for UDP, TCP and ICMP based pkts on Instances
6. NAT-GW Maintained by AWS, NAT-Instances maintained by customer
