# Owning-a-System: Post-Exploitation & Privilege Escalation Simulation

This project simulates the post-exploitation phase of a cybersecurity attack, focusing on maintaining access, escalating privileges, and cracking sensitive passwords on a compromised system. Utilizing tools like John the Ripper and leveraging virtualization platforms such as Microsoft Azure and Hyper-V, this exercise demonstrates the methodologies employed by attackers to fortify their foothold within a target environment.

---

## 🛠 Tools & Techniques Utilized

| Tool / Technique             | Purpose / Security Functionality                                         |
|------------------------------|---------------------------------------------------------------------------|
| **Microsoft Azure Cloud**    | Hosting and managing virtualized environments for testing and simulation  |
| **Hyper-V Virtualization**   | Creating and managing virtual machines for isolated testing environments  |
| **Linux Target Machine**     | Simulating a compromised Linux system for post-exploitation activities   |
| **John the Ripper**          | Cracking password hashes to retrieve plaintext passwords                  |
| **SSH**                      | Establishing secure backdoor access to the compromised system            |
| **sudo**                     | Granting elevated privileges to user accounts                             |

---

## 🎯 Objectives & Key Outcomes

| Objective                                  | Methodology & Tools Employed                                      | Outcome / Recommendations                                           |
|--------------------------------------------|-------------------------------------------------------------------|----------------------------------------------------------------------|
| **Maintain Access**                        | Created a secret user with full sudo access and SSH backdoor      | Ensured persistent access to the compromised system                  |
| **Privilege Escalation**                   | Assigned a system ID to the new user and granted administrative privileges | Elevated user privileges to root level                               |
| **Password Cracking**                      | Utilized John the Ripper to crack password hashes                  | Retrieved plaintext passwords for further exploitation               |
| **Data Exfiltration**                      | Accessed and extracted sensitive data from the compromised system  | Demonstrated potential data breach and information leakage           |
