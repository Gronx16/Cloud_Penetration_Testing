# CloudPenetrationTesting

Cloud computing environment is used to store your files remotely. We are going to create our own cloud environment and harden it’s security by implementing AV and IDS, Honeypot.
We will do penetration testing on this harden secure cloud network.

Cloud Creation:
1. Create a cloud environment by using WAMP/LAMP and own cloud.
2. Create user’s and groups
3. Allow user to share files and limit the disk usage to 2 GB/user

Security:
1. Secure ownCloud from Malicious files uploads using CalmAV
2. Configure IDS (Snort), configure rule for http, icmp
3. Configure Honeypots so that attackers check open ports and try to attack on server

Penetration Testing:
1. Try to Bypass CalmAV in cloud and Hack Windows/Linux OS
2. Implement DoS attack on Cloud Server
3. Report all the findings and vulnerabilities
4. Report the attack type and tools which you gather from IDS and Honeypots
