SOC Threat Hunting and Incident Response
-----

Objective
To simulate a real-world cyber attack and demonstrate SOC analyst skills including network traffic analysis, log analysis, SIEM monitoring, phishing detection, and incident response.

-----

Project Overview
This project integrates multiple cybersecurity techniques into a single SOC workflow. It demonstrates how an organization detects and responds to a phishing-based attack using various tools and analysis methods.

-----

Attack Scenario
A phishing attack targeted an organization where employees received fake emails appearing to be from a bank.
The email contained malicious links. When clicked, attackers attempted unauthorized access, resulting in multiple failed login attempts and SIEM alerts.

-----

Incident Timeline
10:00 AM – Phishing email received  
10:05 AM – User clicked malicious link  
10:06 AM – Failed login attempts detected  
10:07 AM – SIEM alert triggered  
10:10 AM – SOC investigation started  
10:20 AM – Containment actions applied

-----
Phase 1: Detection
Suspicious phishing email identified
Fake domain detected
Malicious link observed
Multiple failed login attempts
SIEM alerts generated
-----
Phase 2: Analysis
Email domain mismatch
Suspicious URL structure
Brute-force login attempts
SIEM alerts confirm anomaly
-----
Phase 3: Containment
Phishing email removed (simulation)
Malicious domain blocked
URL access restricted
Compromised account disabled
-----
Phase 4: Eradication
Malicious files removed (simulation)
System scanned for threats
Passwords reset
Malicious processes terminated
-----
Phase 5: Recovery
Account restored securely
Multi-Factor Authentication enabled
System monitoring continued
Services restored
-----
Indicators of Compromise (IOC)
Suspicious email domain
Malicious URL
Multiple failed login attempts
Unknown IP activity
-----
SOC Workflow
Phishing Email → User Click → Login Attempts → SIEM Alert → SOC Analysis → Response
------

Screenshots
Include images from:
Network analysis (Wireshark)
Log analysis
SIEM (Splunk)
Phishing email
Incident response

-----
Key Learnings
End-to-end SOC workflow
Importance of SIEM monitoring
Phishing attack detection
Incident response lifecycle
Real-world cybersecurity practices

-----

⚠️ Incident Severity
HIGH
-----

✅ Conclusion
This project demonstrates how SOC analysts detect, analyze, and respond to cyber threats using a structured approach. It reflects real-world cybersecurity operations and practical skills required for SOC roles.
------
