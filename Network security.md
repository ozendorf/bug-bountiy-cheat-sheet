### Passive reconnaissance

Tools: 
- whois to query WHOIS servers
- nslookup to query dns servers
- dig to query dns servers

online service:
DNSdumpsters
shodan.io

### Active reconnaissance

Nmap
tip for firewall reconnaissance: using ack scan for based on which ACK packets resulted in responses, you will learn which ports were not blocked by the firewall. In other words, this type of scan is more suitable to discover firewall rule sets and configuration.
-> use -sA

a similar one is the window scan (-sW)


### MITM attacks 
- Ettercap : https://www.ettercap-project.org/
- Bettercap : https://www.bettercap.org/

### Password attacks
- wordlists: https://www.kaggle.com/datasets/wjburns/common-password-list-rockyoutxt
- password attack tool: https://github.com/vanhauser-thc/thc-hydra
  - Typical command line: hydra -l username -P wordlist.txt server service

Mitigation against such attacks can be sophisticated and depends on the target system. A few of the approaches include:

    Password Policy: Enforces minimum complexity constraints on the passwords set by the user.
    Account Lockout: Locks the account after a certain number of failed attempts.
    Throttling Authentication Attempts: Delays the response to a login attempt. A couple of seconds of delay is tolerable for someone who knows the password, but they can severely hinder automated tools.
    Using CAPTCHA: Requires solving a question difficult for machines. It works well if the login page is via a graphical user interface (GUI). (Note that CAPTCHA stands for Completely Automated Public Turing test to tell Computers and Humans Apart.)
    Requiring the use of a public certificate for authentication. This approach works well with SSH, for instance.
    Two-Factor Authentication: Ask the user to provide a code available via other means, such as email, smartphone app or SMS.
    There are many other approaches that are more sophisticated or might require some established knowledge about the user, such as IP-based geolocation.

Using a combination of the above approaches is an excellent approach to protect against password attacks.
