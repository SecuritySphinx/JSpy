# JSpy
This script performs reconnaissance on a list of domains. It creates directories for storing output, extracts headers and response bodies from each domain, extracts script endpoints and downloads scripts, extracts relative URLs from scripts, and runs nmap scans on each domain.

Prequriment
1. Make file name `scope.txt` that file contaiin single main domain your tagert 
> cat scope.txt 
att.com
