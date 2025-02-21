# Opswork For Chef and Puppet
1. Used for configuration management 
2. Supports use of alb and classic elb
3. Logs are stored in s3
4. Autoscailing by default includes all subnet, can be changed to use specific subnets
5. Systems Automation runbook derived from migration of Custom cookbook require manual execution
6. During migration or creation  EBS volumes are created and attached but not mounted 
7. Script to create volumes only copies configuration of volume and not the actual data
