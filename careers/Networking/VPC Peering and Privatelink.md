# VPC Peering V/s Privatelink

1. Peering connects two vpcs, Privatelink connects vpc to specific aws services
2. Peering uses private ip address, Privatelink uses network load balancers and endpoints
3. Peering offers network level access controls, Privatelink offers granular control
4. In peering cost is based on data throughput between vpc, cost is based on data processed by endpoints and no of endpoints
5. In peering cross-region support is available to use, cross-region support is available but efficiency takes hit