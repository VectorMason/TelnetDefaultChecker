# TelnetDefaultChecker
Python script to mimic Legion's telnet default credential brute forcer. 
        
When legion doesn't work.
        
Requires Legion for the bruteforce wordlist.
           
USAGE:
-t: TARGET IP ... 
-f: TARGET FILE ... Target file should include 1 target per line in syntax <IP>:<PORT>
python3 telnetdefault.py -t <IP>  
python3 telnetdefault.py -f <path/to/file>
