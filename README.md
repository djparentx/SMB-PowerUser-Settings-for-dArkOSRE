# How to use:
1) Place in Tools folder
2) Run once
3) It self deletes after successful execution

---

# Features:
- removes useless 'Nobody' folder
- grants root privilege to all smb shares
- optimizes SMB settings

---

PowerUser:
- no root folder access
```ini
# [root]
   # comment = ROOT
   # path = /
   # browsable = yes
   # read only = no
   # map archive = no
   # map system = no
   # map hidden = no
   # guest ok = yes
   # force user = root
```
   
SuperUser:
- root folder access
```ini
[root]
   comment = ROOT
   path = /
   browsable = yes
   read only = no
   map archive = no
   map system = no
   map hidden = no
   guest ok = yes
   force user = root
```
