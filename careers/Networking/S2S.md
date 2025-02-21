# Site-to-Site
1. Each tunnel supports 1.25 GBPs of max throughput
2. DescribeVPN api call can tell state of VPN
3. If VPN status = available then we will be billed
4. When using IPSec each packet in a data stream is authenticated and encrypted
5. Connections can be statically routed or dynamically routed
6. Statically routed vpn are suited for small, dynamically are suited for large
7. Statically requires manual administration of routes, dynamically use BGP protect to learn and keep routes updated
8. Statically routed vpn requires manual intervention during failover, dynamically routed ones failover automatically
9. S2S using Private IP supported for TGW and DX Connect Transit Virtual Interfaces