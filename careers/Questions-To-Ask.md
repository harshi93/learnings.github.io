# Before Meetings?

1. What is the Problem at hand ?
2. What is the expectation from me and the meeting as a whole ?
3. What are some of the blockers, if any
4. Are there assumptions or observations you should be aware of before going into the meeting?

# During Incidents
1. What is the error
2. When did the incident got first reported
- how many customers impacted
- the impact is internal or external
3. What components or services are impacted
4. Did we reach out developers owning the application ?
5. What are our options to restore service ?

# Post Incident
1. Do we know what triggered the problem
2. Are there symptoms that we can alert on

# Change Requests
1. What is changing ?
2. What is triggering a change ?
3. Impact of change is isolated or does affect more than 1 service
4. Do we have all the necessary approvals ?
5. Do we need to send out communication ?
6. Will app be accessible During the change or down ?
7. Do we have 
> - Required ports opened in network
> - Proxy configurations in place 
> - IPs whitelisted
> - Database tables created 
> - Database users created
> - Database index created
> - Kafka topics created 
> - Alert rules setup 
> - Logging levels tuned
8. Is this high traffic application
9. Known Observations/Bugs ? 