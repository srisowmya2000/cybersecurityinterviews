# Cybersecurity Interview questions Key notes 


Q1. What is OSI model?
A1. OSI model is theoritical model which is used to know how two devices communicate in a network. It has 7 layers starting physical, data link, network, transport, session, presentation and application layer. 

Q2. What does each layers do ?
A2. Physical layer: It is more responsible for physical components like fibre cable. It transmits raw bit stream over physical medium. Data link layer: It is responsible for node-to-node data transmission. Ethernet and PPP are the protocols used in this layer. In Network layer it is responsible for packet forwarding throuch routers and IP is the key protocol used.Transport layer is used to provide reliable data transfer to upper layers and TCP, UDP are the main protocols used in this layer. Session Layer it is used to establish, manage and terminate sessions between applications. Presentation layer is more repsonsible for data encryption, compression and conversion. Applciation layer it interfaces directly with application to omanage user interactions. Protocols lilke HTTP,SMTP, DNS are used in this layer.

Q3. Difference between hashing and encryption?
A3. main  difference is that the encryption is reversible and hashing is not reversible. 

Q4. What are different types of Encryption?
A4.Symmetric encryption, Asymmetric Encryption, Hash-based Encryption are the main types of encryption. There are other ones too. 

Q5.What is NIST 800-53?
A5.NIST 800-53 is a catelog for Security and Privacy Control for Federal Infomration Systems and Organisation to protect their information from wide range of Threats.It has 18 control families which emcompasses various security concepts like identification and authentication, audit and accountability, and system and communications protection.Overall, it ensures robust security and privacy programs to safeguard their information and information systems against a wide range of threats.

Q6. What is PCI DSS?
A6.Payment Card Industry Data Security Standard- It is a set of security standards designed to ensure that all companies that accept, process, store, or transmit credit card information maintain a secure environment.It has 6 main controls which include secure network and systems, protect cardholder data , maintain vulnerability management program , impliment strong access control, regular monitoring and main an information security policy. 

Q7. What is HIPPA?
A7.Health Insurance Portability and Accountability Act - Privacy Rule establishes national standards for the protection of individuals' medical records and other personal health information. Security Rule sets standards for the security of electronic protected health information.

Q8.What is Active directory?
A8. It is a centralized database that stores and manages information about network resources, including user accounts, groups, computers, printers, and other network devices

Q9. Name few firewalls, SIEM,routers ?
A9. Firewall: Cisco ASA , Palo Alto Networks NGFW, Fortinet Fortigate Firewall, Checkpoint Firewall, Juniper Networks SRX series Services Gateways.
SIEM: SPLUNK, IBM QRadar SIEM , LogRhythm NextGen SIEM platform, ArcSight Enterprise and Elsatic Security. 
Router: Cisco ISR, Juniper Networks MX Series, Huawei NE series , MikroTik RouterOS.

Q10. Give key components of Active Directory ?
A10. Domain Service, Domain Controller, Organisational Unites, Group Policy, LDAP and Kerberos. 

Q11. What is Domain Services and Domain Controllers?
A11. ADDS: It is responsible for storing directory data and managing domain objects such as users, groups, and computers. It provides centralized authentication and authorization services, allowing users to log in to the network and access resources based on their permissions.
ADDC: Domain controllers are servers that run Active Directory Domain Services and store a copy of the Active Directory database.They authenticate users, enforce security policies, and replicate directory data to ensure consistency across the network.

Q12. What is SSO?
A12. Single Sign-On is an authentication mechanism that allows users to log in to multiple applications or systems using a single set of credentials. It uses various authentication mechanisms, including username/password, tokens, and federated authentication protocols such as SAML (Security Assertion Markup Language) and OAuth.

Q13. What is SIEM?
A13. SIEM-Security Information and Event Management is a security tool. It is a system collects, aggregates, correlates, and analyzes log data and security events from various sources across an organization's IT infrastructure, including network devices, servers, applications, and security appliances.

Q14. Important Protocols
A14. TCP: Transmission Control Protocol. It is Transport layer protocol. Used to deliver data packets over newtwork. It is Connection-Oriented and reliable. 
IP: Internet Protocol: It is responsible for addressing and routing packets of data so that they can travel across networks and arrive at the correct destination.
HTTP: It defines how messages are formatted and transmitted, enabling web browsers to communicate with web servers.
SSL/TLS: Secure Sockets Layer (SSL) / Transport Layer Security (TLS): SSL and its successor TLS are cryptographic protocols used to secure communication over a computer network. They Provide encryption, authentication and data integreity. 
SMTP:Simple Mail Transfer Protocol :SMTP is a protocol used for sending email messages between servers
DNS:It translates domain names into IP addresses, allowing users to access websites and services using human-readable names.
DHCP:Dynamic Host Configuration Protocol -It is a  network management protocol used to automatically assign IP addresses and other network configuration parameters to devices on a network.
BGP: Border Gateway Protocol is a routing protocol used to exchange routing information between autonomous systems on the Internet. It determines the best path for data packets to travel across the Internet and helps routers make routing decisions.
OSPF:Open Shortest Path First is a link-state routing protocol that operates within an autonomous system. It uses the Shortest Path First (SPF) algorithm to calculate the shortest path to each destination and converges quickly in response to network changes.
FTP: File Transfer Protocol is a protocol used for transferring files between a client and a server on a computer network.
SSH: Secure Shell is a cryptographic network protocol used for secure remote access to computers and network services
SMB: SMB stands for Server Message Block. It is a network communication protocol used for providing shared access to files, printers, and other resources on a network.

Q15. What is Ci/CD pipeline?
A15.Continuous Integration is the practice of frequently integrating code changes into a shared repository, such as Git, and automatically running tests and code quality checks on the integrated code.
Continuous Deployment is the practice of automatically deploying code changes to production or staging environments after they have passed through the CI phase.

Q16.
