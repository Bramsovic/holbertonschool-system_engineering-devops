# 🌐 Web Infrastructure Design

> Learn the essentials of designing robust, scalable, and secure web infrastructures.  

---

## 📚 Project Overview

This project focuses on understanding and designing various types of web infrastructures, from simple single-server setups to complex, distributed, and secure architectures. You will practice creating **network diagrams**, explaining the purpose of each component, and identifying potential weaknesses like **Single Points of Failure (SPOF)**.

---

## 🎯 Learning Objectives

By the end of this project, you should be able to:

- Draw and explain the architecture of common web infrastructures
- Describe the roles of web servers, application servers, databases, and load balancers
- Identify and mitigate SPOFs
- Understand the basics of scaling, high availability, and security
- Recognize key concepts like **LAMP**, **SPOF**, **QPS**, **Active-Active vs Active-Passive** setups

---

## 🛠️ Requirements

- **README.md** at the root of the project directory is **mandatory**
- All diagrams must be created using whiteboarding tools, pen and paper, or diagram software
- Upload diagrams to an image hosting service (e.g., **imgur**)
- Insert links to the diagrams in the corresponding task files
- Keep explanations concise and to the point, as in real-world interviews

---

## 📁 Project Structure

```
web_infrastructure_design/
├── 0-simple_web_stack                # Single server LAMP stack
├── 1-distributed_web_infrastructure  # Multi-server distributed infrastructure
├── 2-secured_and_monitored_web_infrastructure  # Secure and monitored setup
├── 3-scale_up                        # Scalable infrastructure
└── README.md                         # Project documentation
```

### 📄 File Descriptions

- **0-simple_web_stack**  
  - Basic single server infrastructure with a **LAMP** stack.
  - Covers **DNS**, **Web server (Nginx)**, **App server**, **Database (MySQL)**.
  - Identifies SPOF and scaling issues.

- **1-distributed_web_infrastructure**  
  - Distributed setup with multiple servers and a **load balancer**.
  - Introduces database replication and load balancing techniques.

- **2-secured_and_monitored_web_infrastructure**  
  - Adds **firewalls**, **SSL** for encrypted traffic, and **monitoring** for enhanced security.
  - Discusses data collection and security considerations.

- **3-scale_up**  
  - Further scales the infrastructure by separating components across dedicated servers.
  - Focuses on reducing latency and increasing reliability.

---

## 📝 Tasks

1. **Simple Web Stack**  
   - Design a single server infrastructure for **foobar.com**.
   - Identify potential weaknesses like SPOF and scaling issues.

2. **Distributed Web Infrastructure**  
   - Add multiple servers and a **load balancer**.
   - Introduce database replication for high availability.

3. **Secured and Monitored Web Infrastructure**  
   - Add **firewalls**, **SSL** encryption, and monitoring tools.
   - Discuss security and performance considerations.

4. **Scale Up**  
   - Further separate components for optimized performance and reliability.

---

## 📎 Resources

Make sure to review:

- [Network Basics](https://intranet.hbtn.io/concepts/33)  
- [Server Basics](https://intranet.hbtn.io/concepts/67)  
- [Web Server Basics](https://intranet.hbtn.io/concepts/68)  
- [DNS Basics](https://intranet.hbtn.io/concepts/12)  
- [Load Balancer Basics](https://intranet.hbtn.io/concepts/46)  
- [Monitoring Basics](https://intranet.hbtn.io/concepts/13)  
- [What is a Database](https://en.wikipedia.org/wiki/Database)  
- [Difference Between Web Server and App Server](https://en.wikipedia.org/wiki/Web_server#Web_server_software)  
- [DNS Record Types](https://en.wikipedia.org/wiki/List_of_DNS_record_types)  
- [Single Point of Failure (SPOF)](https://en.wikipedia.org/wiki/Single_point_of_failure)  
- [High Availability Cluster](https://en.wikipedia.org/wiki/High-availability_cluster)  
- [What is HTTPS](https://en.wikipedia.org/wiki/HTTPS)  
- [What is a Firewall](https://en.wikipedia.org/wiki/Firewall_(computing))  

---

## 🧑‍💻 Author
 
Web Infrastructure Design Project

---
