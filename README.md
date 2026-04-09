# nmap-Enumeration (Mac Edition)

## 1. Install nmap:
   - Open Terminal
     
     ***`brew install nmap`***

## 2. Full Scan:
   - In Terminal

     ***`nmap -sS -SV -O -p- <target ip> -oX <file name.xml>`***

     This will run a full scan of the ip address and save the results in a file in XML format


## 3. Vulnerability Scan:
   - in Terminal

     ***`nmap --script vuln <target ip address>`***

     This will run a vunerability scan of all port and print out the results on screen
     
    
