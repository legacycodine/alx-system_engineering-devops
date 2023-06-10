# Server Outage Incident report

> By Adebimpe Esther Ayooluwa

# Summary Report

![](https://t3.ftcdn.net/jpg/04/92/09/72/240_F_492097246_yagE8x9Uk8M9IekPy7GBuE0x1Uoa7esD.jpg)

On March 6th, 2023, at 5am GMT +0, we encountered a server outage (downtime) across our entire server infrastructure, which persisted for 3 hours and 20 minutes. This unfortunate incident resulted in our clients experiencing an HTTP 500 error, leading to a disruption in our services and preventing our clients from accessing our site. We deeply regret the disruption caused and take full responsibility for the incident.

Upon investigation, it was determined that the root cause of the outage was a hardware failure in our server room that led to the issues that ultimately caused the service disruption. We understand the gravity of this and are taking immediate steps to prevent similar incidents from occurring in the future.

We sincerely apologize for any financial losses, inconvenience, and frustration our clients may have experienced as a result of this incident. We value our clients' trust and will work diligently to regain it by implementing more rigorous emergency backups and enhancing our infrastructure's stability.

# Timeline (all time in GMT + 0)

| Time (GMT + 0) | Actions                                        |
| -------------- | ---------------------------------------------- |
| 4:34 AM        | Power overload on server infrastructure        |
| 5:00AM         | Server Outage begins                           |
| 5:02AM         | Pagers alerted on-call team                    |
| 5:10AM         | On-call team acknowledgement                   |
| 6:15AM         | Backup Systems configuration initiation begins |
| 7:50AM         | Successful rollback                            |
| 8:00AM         | Server restart initiated                       |
| 8:20AM         | 100% of traffic back online                    |
|                |

# Root cause

At 4:34am (GMT +0), our power systems at the server room experienced a power overload causing multiple systems to fail.

Upon discovering the issue, we initiated a backup plan to resolved the servers to their previous state. Afterward, we proceeded with upgrading the current version on our servers to prevent any future disruptions in such order.

We sincerely apologize for the inconvenience caused. We understand the impact it had on our clients' ability to access our services and the resulting downtime. We take full responsibility for this error and have already taken steps to prevent similar occurrences in the future.

Moving forward, we will reinforce our power infrastructure to the servers. Our team is committed to maintaining the stability and reliability of our infrastructure and services to avoid any further interruptions.

# Preventive measures

- Review the current power systems to the server room.
- Implement a more robust backup system to ensure data integrity and availability.
- Increase the performance metrics threshold to alert on-call engineers in the event of possible server crash.

Adebimpe Esther
https://www.linkedin.com/pulse/server-outage-incident-report-esther-adebimpe
Alx Project.

