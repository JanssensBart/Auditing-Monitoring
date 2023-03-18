# SNMP 
## (**S**)imple (**N**)etwork (**M**)anagement (**P**)rotocol

## Setup config file

**linux**

1. ```cd ~```
2. ```mkdir .snmp```
3. ```vi snmp.conf``` 

```sh
defVersion 3
defSecurityLevel AuthPriv
defSecurityName <username>
defPassphrase <pswd>
defAuthType SHA
defPrivType AES
```
4. save config 
5. check => ```cat snmp.conf```