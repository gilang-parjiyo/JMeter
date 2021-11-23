# How to run
```
jmeter -n -t demo\Restfull-booker.jmx
```

# Rum up period
**Jmeter Thread Group**
- Number of Thread > number of users connect to the target website: 
- Loop count 10 (Number of time to execute testing).
- Ramp-up period 100 > delay before next user.
- Ramp-Up Period tells JMeter how long to delay before starting the next user. For example, if we have 100 users and a 100-second Ramp-Up period, then the delay between starting users would be 1 second (100 seconds /100 users)