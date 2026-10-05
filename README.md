# fleet-uptime

Independent availability checks for **https://fleetmngmnt.com** (GPS fleet
management platform), used as SLA evidence.

Every ~5 minutes a GitHub-hosted runner requests the site and its API health
endpoint from outside the hosting provider's network. The timestamped run
history below is the availability log; a failed run means the service did not
return HTTP 200 at that moment.

No application code or customer data lives here.
