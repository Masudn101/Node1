# Node1
![Screenshot 2024-05-30 at 7 22 43 PM](https://github.com/Masudn101/Node1/assets/39289859/04f24869-828b-4a15-8067-760921591211)




```
Get-NetFirewallProfile | FL Name,Enabled
```
```
Set-NetFirewallProfile -Profile Domain,Public,Private -Enabled True
```
```
Set-NetFirewallProfile -Profile Domain,Public,Private -Enabled False
```
```
Get-NetFirewallProfile | FL Name,Enabled
```
```
Get-NetAdapter
```

```
New-NetIPAddress -InterfaceAlias "Ethernet" -IPAddress "192.168.10.201" -PrefixLength 24 -DefaultGateway "192.168.10.254"
```
To setbackDHCP

```
Set-NetIPInterface -InterfaceIndex 12 -Dhcp Enabled
```

#could not add without -interfaceindex ....

```
Set-DnsClientServerAddress -InterfaceAlias "Ethernet" -ServerAddresses ("192.168.10.1","192.168.10.2")

```

Join Domain

```
Add-Computer -DomainName abc.com
```
![Screenshot 2024-05-30 at 8 00 21 PM](https://github.com/Masudn101/Node1/assets/39289859/33174270-04c9-44aa-b8cf-56a31f87ee74)









