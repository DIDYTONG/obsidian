

#### Naming Contexts

```
ldapsearch -H ldap://10.10.10.161 -x -s base namingcontexts
```

```
ldapsearch -H ldap://10.10.10.161 -x -b 'DC=EGOTISTICAL-BANK,DC=LOCAL'
```

```
ldapsearch -H ldap://10.10.10.100 -x -b DC=HTB,DC=LOCAL "(ObjectClass=person)" | grep "sAMAccountName:"
```
