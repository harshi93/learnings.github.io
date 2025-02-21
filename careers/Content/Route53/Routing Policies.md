# Routing Policies
1. Additionally supports simple, failover, ip, multivalue, geolocation, geoproximity, weighted round robin, latency
2. Supports weighted round robin, useful for A/B testing
3. Supports Latency based routing, useful for applications at edge
4. Supports Geo DNS, useful for routing requests matching compliance and localization requirements 
    a. Geo DNS require global record to handle requests from ips that are in geo databse
5. Route 53 defaults to IP for browser clients that don’t support EDNS0, uses EDNS0-client-extension  for those that support it
6. EDNS0 is only available to route DNS queries response for records in public hosted 
7. For private hosted zone, r53 relies on r53 resolvers