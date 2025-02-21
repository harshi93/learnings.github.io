# DNS
1. Translates names to IP
2. Hosted zone is similar to DNS Zone
3. Route53 uses anycast
4. We can import zone file from DNS Bind Severs
5. There can be multiple hosted zone for same domain name 
6. Wildcard entries are support for all records except for NS type
7. DNS record changes are transactional aka it will either happen or wont happen, no middle state
8. Changes propogate in 60 seconds under normal conditions
9. Supports DNSSEC signing, validation and enablement
10. Route53 supports simple, failover, geolocation, geoproximity, ip, multivalue, latency, weighted
