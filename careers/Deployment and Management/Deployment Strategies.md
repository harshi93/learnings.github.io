# Deployment Strategies

# Rolling 
    - wait for 1 pod to come online before proceeding next old one 
# Revamped Slow Rollout 
    - more finer rollout controls are available like maxSurge and maxUnavailable
# A/B 
    - redistribution of traffic based on number of requests
# Shadow 
    - for testing and monitoring without live traffic
# Recreate 
    -  Involves downtime
    - All pods are recreated at once
