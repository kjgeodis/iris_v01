---
tags: [Security, Authentication, Milestones, IRIS]
---
![IRIS API](../../assets/images/IRIS_API_147_110.png)
# Security-and-authorization

## Authentication
For all web service requests authentication of the user credentials are required. The
username and password will be provided by GEODIS. Please be aware that the username and password
required for the IRIS API is not the same as an IRIS user account. Likewise, the username and password
for the IRIS API cannot be used to login to web interface of the IRIS eSolution platform.

## Blacklisting of IP addresses
Please be aware that the IRIS API system will automatically block access
from any IP address using the services and where usage is considered as misuse. IP addresses will also
automatically be blocked for a period of time if incorrect username and/or password is being used
multiply times.