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
![Screenshot 2024-05-30 at 8 01 26 PM](https://github.com/Masudn101/Node1/assets/39289859/0c10a4dc-9745-4fc5-8b55-bceff47e6925)











