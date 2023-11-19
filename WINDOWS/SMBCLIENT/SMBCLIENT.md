

### Anonymous login 

```
smbclient -N -L //10.10.10.175
```


### Login with User

```
smbclient -L 10.10.10.175 -U "Egotistical-bank.local/fsmith"

smbclient //10.129.193.5/Users -U active.htb/svc_tgs
```

### Login to share

```
smbclient //10.129.193.5/Replication
```
