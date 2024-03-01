<p align="center">
    <img [Web infrastructure design] src="https://cdn.discordapp.com/attachments/1186717231644676196/1213243569385504818/Web_infrastructure_design.jpg?ex=65f4c41f&is=65e24f1f&hm=031e24715ac378baa38a1f3157ca6bcb4ea524337564bc11b8d31f406877438a&">
</p>

----------

# <p align="center">Web infrastructure design</p>


## ➤ Description:

Summary of basic network concepts and web infrastructure :
**Basic network concepts:**
1. **Network:** A collection of devices connected to share resources and communicate.
2. **Internet:** Global network linking millions of networks using TCP/IP.
3. **Protocols:** Rules governing the transmission of data over a network (e.g. TCP/IP, HTTP).
4. **IP address:** Unique identifier assigned to each device on a network (IPv4, IPv6).
5. **DNS:** System that translates domain names into IP addresses.
6. **Router:** Selection of the best path for data transmission.
7. **Switching:** Transfer of data packets between devices on the same network.
8. **Firewall:** Network security device controlling incoming/outgoing traffic.
9. **OSI model:** Seven-layer reference model for network communications.
10. **LAN/WAN:** Local area networks (small area) vs. wide area networks (large area).
11. **IP addresses:** IPv4 and IPv6.
12. **TCP/UDP:** Data transfer protocols over IP.
13. **Ports:** Numbers identifying applications/services on a device.
14. **SSH/HTTP/HTTPS port numbers:** SSH (22), HTTP (80), HTTPS (443).
15. **ICMP:** Protocol for checking connectivity of network devices.

**Web infrastructure:**
1. **Application Server:** Executes application code, processes client requests.
2. **Database Server:** Stores and manages application data.
3. **Web Server:** Receives HTTP requests from clients and redirects them to the appropriate application.
4. **DNS/Load Balancer Server:** Manages network traffic routing, ensuring balanced load distribution.
5. **Firewall:** Controls and filters incoming and outgoing network traffic, ensures system security.
**System redundancy:** Implementation of additional components to ensure continued availability of services in the event of failure.
**Acronyms:**
- **LAMP :** Linux, Apache, MySQL, PHP.
- **SPOF :** Single Point of Failure.
- **QPS:** Requests Per Second.

----------

## ➤ Concepts

For this project, we expect you to look at these concepts:

* [Network basics](https://intranet.hbtn.io/concepts/791)
* [Server](https://intranet.hbtn.io/concepts/799)
* [Web Server](https://intranet.hbtn.io/concepts/800)
* [DNS](https://intranet.hbtn.io/concepts/803)
* [Load balancer](https://intranet.hbtn.io/concepts/804)
* [Monitoring](https://intranet.hbtn.io/concepts/805)

## ➤ Resources:

Read or watch:

* Network basics concept page
* Server concept page
* Web server concept page
* DNS concept page
* Load balancer concept page
* Monitoring concept page
* [What is a database](https://intranet.hbtn.io/rltoken/7Pp0_Mdit6r_ZdRGKAwcqw)
* [What’s the difference between a web server and an app server?](https://intranet.hbtn.io/rltoken/YqKvabbDDtSjnHMV9g1gHw)
* [DNS record types](https://intranet.hbtn.io/rltoken/kZXE57FUOK-cqmLfN3CWfg)
* [Single point of failure](https://intranet.hbtn.io/rltoken/56OIJ23o5mqSaSeLEwxzJg)
* [How to avoid downtime when deploying new code](https://intranet.hbtn.io/rltoken/lxwkY5pRIVzatMPXwx6yew)
* [High availability cluster (active-active/active-passive)](https://intranet.hbtn.io/rltoken/rITwKN4AKP1hXZl2FKcAcw)
* [What is HTTPS](https://intranet.hbtn.io/rltoken/iEaO7X54UemiSN9z8TtFVA)
* [What is a firewall](https://intranet.hbtn.io/rltoken/P2A36USOkcekiqHsCzTefQ)

----------

## ➤ Requirements:

General

* A README.md file, at the root of the folder of the project, is mandatory
* For each task, once you are done whiteboarding (on a whiteboard, piece of paper or software or your choice), take a  picture/screenshot of your diagram
* This project will be manually reviewed:
* As each task is completed, the name of that task will turn green
* Upload a screenshot, showing that you completed the required levels, to any image hosting service (I personally use imgur but feel free to use anything you want).
* For the following tasks, insert the link from of your screenshot into the answer file
* After pushing your answer file to GitHub, insert the GitHub file link into the URL box
* You will also have to whiteboard each task in front of a mentor, staff or student - no computer or notes will be allowed during the whiteboarding session
* Focus on what you are being asked:
* Cover what the requirements mention, we will explore details in a later project
* Keep in mind that you will have 30 minutes to perform the exercise, you will get points for what is asked in requirements
* Similarly in a job interview, you should answer what the interviewer asked for, be careful about being too verbose - always ask the interviewer if going into details is necessary - speaking too much can play against you
* In this project, again, avoid going in details if not asked