# oSSH wordlists
These lists are updated daily and can be used for internal security scans, username and password policies, intrusion detection, IP reputation decisions, and so on. Feel free to use them for any purpose. If you want to run your own oSSH cluster to collect data like this, check out the [oSSH repo](https://github.com/toxyl/ossh).  

Currently these lists are available:  
- users.txt: 60839                                                                                                                                                                                             Usernames used by bots to login. 
- passwords.txt: 190826                                                                                                                                                                                             Passwords used by bots to login. 
- hosts.txt: 94271                                                                                                                                                                                             IPs of the connecting bots. Be aware that they can include IPs of VPNs, Tor exit nodes and others that are NOT IPs of the actual attackers. Furthermore, IPs can get reassigned after being recorded by the honeypot. Therefore this list can not be relied upon, but might be helpful as an indicator.
