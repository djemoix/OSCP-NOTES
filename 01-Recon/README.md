# 🔎 Reconnaissance

## Exiftool
```
exiftool -a -u file
```

## DNS Enumeration
```
dnsrecon -d domain -t std
dnsenum domain
```

## NetBIOS Scan
```
sudo nbtscan -r 192.168.50.0/24
```

## SNMP Enumeration
```
onesixtyone -c community.txt ip
snmpwalk -c public -v1 ip
```

## SMTP User Enum
```
nc ip 25
VRFY username
```
