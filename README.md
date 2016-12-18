# Incidently

> Incidently, pronounced [in-si-dent-lee], is named as an intentional mis-spelling of the word "incidentally" since the long-term goal for the toolset is indeed anything but incidental.  The intent is to ease the effort of communication and tracking of Incidents during the process while also tracking the details in a more standard way.


Dev site: [dev_url]  
Prod site:   

### Current Features

- Define, track, and send Incident Alerts including the following Incident Fields:  
-- Incident Ticket  
-- Incident Owner  
-- Incident Response Team Members (re-usable)  
-- Incident Actions (re-usable)  
-- Products affected (re-usable)  
-- Summary  
-- Incident Start / Creation / Resolution datetimes  
-- Severity (1-5)  
-- PHI relation  
-- Executive involvement  
-- Site outage  
-- Number of Members impacted  
-- GoTo Meeting ID  
- Active Directory Integration  
-- TLS over port 636  
- Email  
-- Recipient list based on product impacted  
- Permissions model  
-- Currently based on Supervisor vs "Author" group only  


### Todo:
- Additional Models  
-- Incident Category  
** Category On-Call team contact definition  
- Hubot Integration  
-- Command to gather Incident Status  
- OpenDuty Integration  
-- Initiate alert to On-Call Team  
-- Show current status for On-Call Alert  
- Testing  
-- Need to write tests for each of the features  


### Tech

Incidently uses a number of open source projects to work properly:

* [django] - High-level Python Web Framework


And of course Incidently itself is open source with a [public repository]
 on GitHub.

### Installation

TBD.



License
----

MIT




[//]: # (These are reference links used in the body of this note and get stripped out when the markdown processor does its job. There is no need to format nicely because it shouldn't be seen. Thanks SO - http://stackoverflow.com/questions/4823468/store-comments-in-markdown-syntax)

   [dev_url]: <https://TBD>
   [django]: <https://github.com/django/django>
   [public repository]: <https://github.com/krutaw/Incidently>

