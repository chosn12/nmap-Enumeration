# nmap-Enumeration (Mac Edition)

## 1. Install nmap:
   - Open Terminal
     
     ***`brew install nmap`***

## 2. Full Scan:
   - In Terminal

     ***`nmap -sS -SV -O -p- <target ip> -oX <file name.xml>`***


     <img width="600" height="500" alt="Full Scan" src="https://github.com/chosn12/nmap-Enumeration/blob/59b93b24e09ddba5b8b5df97690f1219c47ba03b/screenshots/Full%20Scan.png"/>

     This will run a full scan of the ip address and save the results in a file in XML format


## 3. Vulnerability Scan:
   - in Terminal

     ***`nmap --script vuln <target ip address>`***


      <img width="600" height="500" alt="Vulnerability Scan" src=""/>


     This will run a vunerability scan of all port and print out the results on screen
     
    
