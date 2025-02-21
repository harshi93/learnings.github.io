# NAT-T
1. Adds layer of UDP encapsulation to protect IPSec from being discarded translation
2. Enables connecting to resources behind NAT
3. Ensure IPSec connections remain open while traffic is going through NAT
4. NAT-T if not used, needs to be disabled, otherwise tunnel won't establish
5. AWS Defaults to using NAT-T technique
6. Uses ISAKMP to negotiate security parameter
7. Used in main-mode and quick-mode of IPSec
8. Uses port 4500 with ipsec unaware NAT
