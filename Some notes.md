## Enumeration Techniques

### Reconnaissance 

- **nmap**
- **Dirbuster**

### Content Discovery 

- Manual discovery 
    - **robots.txt**
    - **sitemap.xml**
    - **http headers**
    - **Google hacking / dorking:** [https://en.wikipedia.org/wiki/Google_hacking](https://en.wikipedia.org/wiki/Google_hacking)
- Framework discovery 
    - **OWASP favicon database:** [https://wiki.owasp.org/index.php/OWASP_favicon_database](https://wiki.owasp.org/index.php/OWASP_favicon_database)

- OSINT 
    - **Wappalyzer:** [https://www.wappalyzer.com/](https://www.wappalyzer.com/)
    - **Wayback Machine:** [https://archive.org/web/](https://archive.org/web/)

- Automated discovery 
    - **Wordlists:** [https://github.com/danielmiessler/SecLists](https://github.com/danielmiessler/SecLists)
    - **dirb**
    - **gobuster**
    - **ffuf**

- Subdomain Enumeration
    - OSINT
    - Brute Force
    - Virtual hosts
    - **CRT.SH:** [https://crt.sh](https://crt.sh)
    - **CT Search:** [https://ui.ctsearch.entrust.com/ui/ctsearchui](https://ui.ctsearch.entrust.com/ui/ctsearchui)
    - **dnsrecon**
    - **Sublist3r:** [https://github.com/aboul3la/Sublist3r](https://github.com/aboul3la/Sublist3r)



### Vulnerability Management 
- **NVD:** [https://nvd.nist.gov/vuln/full-listing](https://nvd.nist.gov/vuln/full-listing)
- **Exploit Database:** [http://exploit-db.com/](http://exploit-db.com/)

### Authentication Bypass
- User Enumeration: **ffuf:** [https://github.com/ffuf/ffuf](https://github.com/ffuf/ffuf)
- Cookie Hash: [https://crackstation.net/](https://crackstation.net/)

### SSRF
- Look for potential SSRF in 
    - Full URL used as parameter in the address bar
    - Hidden field in a form with application URL
    - Path in URL

### To-Do
- Obtain wordlist for all the notes related to enumeration (see THM for ex)



### Application proxy
- foxy proxy https://addons.mozilla.org/en-US/firefox/addon/foxyproxy-standard/
