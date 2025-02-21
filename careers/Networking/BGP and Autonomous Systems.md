# Border Gateway Protocol
- Set of rules to determine best path to destination
- Uses mechanism called peering
- Each BGP peer sits at the edge of Autonomous systems
- Each BGP peer participates in Route discovery, Route storage and Route Selection
- Each BGP peer knows about it's neighbor
- Each BGP peer collection information such as latency, hop count, cost of transmission

# Autonomous Systems
- Autonomous systems use BGP
- Each AS is a distinct network that broadcasts how it can be reached
- Information provided by AS is then used by other AS on the internet to decide how to best route a packet going to specific destinations
- AS can be an ISP or network of organization
- Each AS has a unique identifier
- AS have their own rules of governance to decide how packets get routed within the network
