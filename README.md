# Applying OS Hardening Techniques

## Objective

This lab focused on investigating a brute force attack that compromised the website yummyrecipesforme.com. Key objectives included analyzing network protocols using tcpdump, identifying the methods used to inject malware into the website's source code, and documenting the incident. The lab also emphasized recommending security measures, such as stronger password policies and defenses against brute force attacks, to prevent similar incidents in the future.

### Skills Learned

- Ability to analyze network traffic and identify protocols involved in security incidents.
- Experience using packet capture tools like tcpdump to investigate suspicious activity.
- Understanding of how malicious actors exploit vulnerabilities, such as brute force attacks, to gain unauthorized access.
- Proficiency in documenting security incidents, including identifying affected systems and protocols.
- Ability to implement preventive measures like disabling previous passwords and enabling two-factor authentication (2FA).
- Enhanced knowledge of common attack techniques, such as malware distribution through compromised websites.
- Practical experience in analyzing and responding to real-world security incidents in a controlled environment.
- Knowledge of incident response procedures, including isolating systems and conducting thorough investigations.



### Tools Used

- tcpdump: A network packet analyzer used to capture and examine network traffic during the investigation of the security incident.
- Sandbox environment: A controlled, isolated environment for safely analyzing the website and malicious file without impacting the company’s network.
- Browser: Used to interact with the compromised website and trigger the malicious download for investigation.



## Steps!

![Screen Shot 2024-12-22 at 1 20 23 AM](https://github.com/user-attachments/assets/0370afc2-6d66-46f6-9906-b5efb157ea30)

Ref 1. This screenshot highlights the investigation process into a security issue affecting the website yummyrecipesforme.com. By analyzing tcpdump logs, network protocols used in the connection were identified, revealing potential malicious activity and informing solutions to protect the network.

![Screen Shot 2024-12-22 at 1 24 39 AM](https://github.com/user-attachments/assets/e1d46c12-d80d-4642-bc7d-ffa348771e72)

Ref 2. This screenshot documents the investigation of a security breach on yummyrecipesforme.com, where a former employee executed a brute force attack to embed malware into the website's source code. By analyzing network traffic and logs, the team identified the malicious activity and recommended measures to prevent future brute force attacks, such as strengthening password policies and implementing multi-factor authentication.

![Screen Shot 2024-12-22 at 1 59 56 AM](https://github.com/user-attachments/assets/0f701417-434b-4b9b-aa34-e6adac5bd6f5)

Ref 3. Screenshot of Incident Documentation and Protocol Analysis: Detailed report identifying HTTP as the protocol used during the attack and outlining the incident investigation process.

![Screen Shot 2024-12-22 at 2 03 02 AM](https://github.com/user-attachments/assets/784ca72e-6350-42d4-978a-dd8f554f6c66)

Ref 4. Screenshot of one or more remediations for brute force attacks

![Screen Shot 2024-12-22 at 2 08 29 AM](https://github.com/user-attachments/assets/b9fb01b8-035b-40f5-a012-8d4147c6c94d)

Ref 5. The DNS request for the IP of yummyrecipesforme.com URL is initiated and replies with the correct IP address

![Screen Shot 2024-12-22 at 2 11 36 AM](https://github.com/user-attachments/assets/de5ca46f-79f2-47f2-8f45-b8b2688d7fa4)

Ref 6. The source computer sends a connection request directly to yummyrecipesforme.com.http which would be port 80

![Screen Shot 2024-12-22 at 2 16 15 AM](https://github.com/user-attachments/assets/f285b222-056f-4e1a-bdc6-b939f0ebfe1e)

Ref 7. This log entry shows the browser requesting data from yummyrecipesforme.com with the HTTP:GET method. This is the download request for the malicious file

![Screen Shot 2024-12-22 at 2 22 40 AM](https://github.com/user-attachments/assets/d7404387-ddb0-4856-b940-76c0ec65353e)

Ref 8. There is a sudden change in logs, traffic is routed to make another DNS resolution request. This time to a new IP address and its associated URL.



