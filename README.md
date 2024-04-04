## Use the NIST-Cybersecurity-Framework to respond to a security incident 
### Scenario
You are cybersecurity analyst working for a multimedia company that offers web design services, graphic design, and social media marketing solutions to small businesses. Your organization recently experienced a DDoS attack, which compromised the internal network for two hours until it was resolved. 

During the attack, your organization’s network services suddenly stopped responding due to an incoming flood of ICMP packets. Normal internal network traffic could not access any network resources. The incident management team responded by blocking incoming ICMP packets, stopping all non-critical network services offline, and restoring critical network services. 

The company’s cybersecurity team then investigated the security event. They found that a malicious actor had sent a flood of ICMP pings into the company’s network through an unconfigured firewall. This vulnerability allowed the malicious attacker to overwhelm the company’s network through a distributed denial of service (DDoS) attack. 

To address this security event, the network security team implemented: 
-	A new firewall rule to limit the rate of incoming ICMP packets
-	Source IP address verification on the firewall to check for spoofed IP addresses on incoming ICMP packets
-	Network monitoring software to detect abnormal traffic patterns
-	An IDS/IPS system to filter out some ICMP traffic based on suspicious characteristics

As a cybersecurity analyst, you are tasked with using this security event to create a plan to improve your company’s network security, following the National Institute of Standards and Technology (NIST) Cybersecurity Framework (CSF). You will use the CSF to help you navigate through the different steps of analyzing this cybersecurity incident and integrate your analysis into a general security strategy:

- Identify security risks through regular audits of internal networks, systems, devices, and access privileges to identify potential gaps in security. 
-	Protect internal assets through the implementation of policies, procedures, training and tools that help mitigate cybersecurity threats. 
-	Detect potential security incidents and improve monitoring capabilities to increase the speed and efficiency of detections. 
-	Respond to contain, neutralize, and analyze security incidents; implement improvements to the security process. 
-	Recover affected systems to normal operation and restore systems data and/or assets that have been affected by an incident

### Incident report analysis
|   | Explanation | 
|---|---|
|Summary| The company experienced a DDoS attack due to flood of incoming ICMP packets. The cybersecurity team found the disruption was caused by a distributed denial of services( DDoS ) attack through a flood of incoming ICMP packets. The team responded by blocking the attack and stopping all non-critical network services. So that critical network services couuld be restored. |
|Identify| Malicious actors targeted the company with an ICMP flood attack. The entire internal network was affected. All critical network resources needed to be secured and restored to a functioning state.| 
|Protect| The cybersecurity team implemented a new firewall rule to limit the rate of incoming ICMP packet and  IDS/IPS system to filter put some ICMP traffic based on suspicious characteristics | 
|Detect| The cybersecurity team configured source IP address verification on the firewall to check for spoofed IP addresses on incoming ICMP packets and implemented networking monitoring software to detect abnormal traffic patterns| 
|Respond| For future security event, the cybersecurity team will isolate affected systems to prevent furthur disruption to the network. They will attempt to restore any critical systems and services that were disrupted by the event. Then, the team will analyze network logs to check for suspicious and abnormal activity. The team will also report all incidents to upper management and appropiate legal authorities, if applicable. | 
|Recover| To recover from a DDoS attack by ICMP flooding, access to network services need to be restored a normal functioning state. In the future, external ICMP flood attacks can be blocked at the firewall. Then, all non-critical network services should be restored first. Finally, once the flood of ICMP packets have timed out, all non-critical network systems and services can be brought back online. | 


