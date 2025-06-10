### 🛡️ Firewall Fundamentals

**Room:** [Firewall Fundamentals — TryHackMe](https://tryhackme.com/room/firewallfundamentals)  
**Status:** ✅ Completed  
**Date:** *10 June 2025* 

---

### 🎯 Objective  
Learn about firewalls, their types, how they filter traffic, and get hands-on practice with built-in firewall tools in both Windows and Linux.

---

### 🗝️ Key Concepts  
- **Firewall** — A security tool that filters incoming and outgoing network traffic based on a set of rules.  
- **Stateless Firewall** — Filters packets based only on predefined rules without tracking connection states.  
- **Stateful Firewall** — Tracks the state of connections and applies rules accordingly.  
- **Proxy Firewall** — Operates at the application layer, inspects packet contents, and masks internal IPs.  
- **Next-Generation Firewall (NGFW)** — Includes advanced features like intrusion prevention, SSL inspection, and threat intelligence.  
- **Firewall Rules** — Instructions that control traffic flow using components like source, destination, port, protocol, direction, and action (allow, deny, forward).  
- **Windows Defender Firewall** — Built-in Windows firewall with GUI and custom rule creation.  
- **ufw (Uncomplicated Firewall)** — Linux front-end for iptables, allowing simpler firewall rule management.

---

### 🛠️ Tools Used  
- **Windows Defender Firewall** — Used to create and test outbound rules for HTTP/HTTPS blocking.  
- **ufw (Linux)** — Used to define and manage inbound and outbound firewall rules with simple commands.

---

### ⚠️ Challenges Faced  
- Remembering the differences between stateless vs stateful firewalls was tricky at first.  
- Testing the firewall rules in Windows required extra care to avoid accidentally locking out all traffic.

---

### 🧠 What I Learned  
- How different types of firewalls function and where they sit on the OSI model.  
- The structure of firewall rules and how to build custom ones based on needs.  
- Hands-on creation of Windows Defender and Linux `ufw` rules to allow/deny specific traffic.  
- How to view, test, and delete firewall rules safely in a controlled environment.

---

### 🌐 Real-World Application:  
> Firewalls are essential for protecting systems and networks from unauthorised access. Knowing how to configure them properly allows you to reduce risk, control traffic, and stop potential intrusions at the perimeter. Skills like creating rules in Windows Defender or `ufw` are valuable for both defensive security roles and system administration.

---

### 💭 Reflections:  
- It was interesting to compare how firewalls work differently across Windows and Linux.  
- Creating real rules and testing their impact helped the concepts stick.  
