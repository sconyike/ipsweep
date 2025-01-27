# ipsweep
A Bash script designed to automatically perform a ping sweep on a /24 subnet. It scans every IP address in the subnet, identifying live hosts for network analysis or troubleshooting. 



How to run:

./ipsweep.sh {ip address}



Frequently Asked Questions:
Question: My bash script is producing an error with “seq”. How do I resolve?
Resolution: Ensure use of backtick (`) instead of using single quote ('). Alternatively, use $(seq 1 254) instead of seq
