# Xframwork Public Version(Under Development) 
(Semi-Automated Vulnerability Scanner and Massive Enumeration Tool/Interpreter For Automateing Standard Tools)
XFramework aims to automate Most of Routine Network/WebApplication Information Gathering, Enumeration and Vulnerability Scanning
it consists of two Base. 1)Network 2)Web-Application
We have Tried to Develop a Semi-Automated Interpreter that its main Goal is Making the routines easier P.Tester its Written Python3 Although Some Of the 3rd party tools are writen c/c++/Ruby/bash/python2

## About Xframework Public Version
### Functions and Tools 
- Network Scanner
  - Network Scanning For Open/Filter Ports 
  - Standard Checks With Using Plugins For TELENT/SSH/SMB/SQL-SERVER/WEB-PORTS
  - Bruteforce Services
- X-Attacker Core 
  - Information Gathering
  - CMS Identifier (More Than 120 CMS)
  - WAF Testing (Enumeration, Limited Firewall Bypass Recommendation) 
  - CMS-ENUMERATION For Drupal/Wordpress/Joomla/Vb
  - Crawler For URLs 
  - LFI, RFI, and RCE
  - Sql-injection 
  - Template-Injection 
  - Basic XSS Check
  - CSRF Scan 
  - Brute force directories and files in websites
  
Note : This Framework Tries To Follow the Standard OWASP Meth. For Pen testing

### What Tools It Automate ?

Automated Tools Names (Not Yet Completed)

- Nmap / Some Nmap Scripts 
- Golismero / Nikto
- CMSmap/WPScan/WPsecu/Droopscan/Joomscan
- Photon
- Sqlmap / Tplmap / Sqliv / XssPy
- Hydra
- Bunch of Other Scrpits/Tools

## Installation
Generally it needs some pre-installed KALI tools such as Nmap/Sqlmap/Golismero/Nikto but the install will install the packages/Libraries/Dependencies That You Need

### Requirments  

This Framework has Beed Developed In Kali Linux For Kali Linux ALthough you might also try it on any DEBIAN distro.
please note that it if you want to use it On Parrot OS / Ubuntu Make Sure Every Single Package Have been Installed Successfully


### Before Installation 
Please Make Sure Your System is Updated
``` 
sudo apt-get update
sudo apt-get upgrade
```

### Auto Way 

```
sudo chmod +x installer.sh && ./installer.sh
```

### Manual Way 

``` 
sudo apt-get nmap golismero sqlmap hydra 
sudo pip requests bs4 
git clone 
```

 # History
The Basic Framework(Scripts) Have Been Developed Around 2015/2016 in Python2/Ruby/Perl and It has Distributed in Some Forums and Among Some Local P.Testers by name of "XMass-Attacker Scripts" with limited Automated Enumeration Tools and Also Exploitation Recommendation. Since The old Version was Kind of Out-of-Date and Not Very Friendly(Flexible) i decided to Write a completely New framework from Scratch.  


# Road Map
##### Under_development 

- Metasploit
- Zmap
- wapiti / WAFW00F / Commix
- Plugin Engine/Wizard (For Using Easy 3rd party Command lines Aside from The Core Tools 
- installer for all tools / packages / python modules / kali libraries

##### TODO.txt
- Xmass Network Attacker Script V2 (Multiprocessed Network Attacker Designed for Brutal Attacks with Extreme Bruteforce Aproch/ Historically Used [Responder/CrackMapExec/Hydra] - Adding New Tools/Optimizing Old Codes)
- SubDomain Discovery Tool ? Maybe Some More Multi-Threaded Semi-Recuresive Dir-Bruteforce ? 
 
