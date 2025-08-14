This project demonstrates how to use a pfSense firewall to block a Denial of Service (DoS) attack in a virtual lab environment.

What You Need
1. VirtualBox
2.ISO files for: pfSense, Kali Linux, and Ubuntu Desktop.

Objective
Simulate a DoS attack from a Kali Linux "attacker" machine against an Ubuntu "victim" machine and use pfSense to stop it.

Verification
The packet flood in Wireshark will stop immediately. The pfSense firewall logs will show that traffic from the attacker is being blocked.
