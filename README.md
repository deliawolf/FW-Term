# FW-Term

A firewall is a system that enforces an access control policy between two or more security zones. 

There are several types of firewalls, but all firewalls should have the following properties:

1. The firewall itself must be resistant to attack; otherwise, it would allow an attacker to disable the firewall or change its access rules.

2. All traffic between security domains must flow through the firewall. This prevents a backdoor connection that could be used to bypass the firewall, violating the network access policy.

3. A firewall must have traffic-filtering capabilities.

Consider the following common deployment scenario for a firewall using three zones:

1. Inside: a private, trusted network

2. Outside: the public, untrusted internet

3. Demilitarized Zone (DMZ): a zone containing servers that are accessible by the public internet

Features in a Cisco Secure Firewall include the following:

1. Cisco URL Filtering: This feature moves the most commonly used proxy server function into the firewall itself, and can take advantage of URL classification and website reputation scores.

2. Application Visibility and Control: This feature recognizes applications by analyzing data streams instead of looking at transport layer port numbers. For example, applications such as Skype, which are capable of hopping from one port to another, can be recognized. Another example is not only recognizing Facebook, but recognizing gaming within Facebook.

3. Context Awareness: Who is connecting, to what, from where, using which device, at what time? Policy can be defined that allows members of the marketing team to access Facebook for marketing purposes, but even they are not allowed to access Facebook games. Also, what a user can access via their corporate managed laptop and what they can access via their personal mobile phone may differ.

4. Cisco Intrusion Prevention System: Again, something that has traditionally been handled by separate systems can now be integrated directly into a firewall appliance, and it can be made even more powerful by utilizing the contextual awareness that is integrated into the next generation firewall.

5. Advanced Malware Protection: This feature can provide detection, blocking, tracking, analysis, and remediation.

