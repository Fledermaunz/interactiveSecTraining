
4) Version Detection  
   nmap -sS -sV -p8008 IP_ADDRESS

5) Timing  
   -T + paranoid (0), sneaky (1), polite (2), normal (3), aggressive (4), and insane (5)

6) Output  
   -v(vvv) (Verbose) to see what's happening during the process. E.g. vvv or v3 is more detailed
   -d for debugging. Similar -d9 is maximum datailed
   - Scan Report in different formats: -oN <filename> (Normal), -oX <filename> (XML), -oG <filename> (Grep), -oA <filename> (all major formats)
