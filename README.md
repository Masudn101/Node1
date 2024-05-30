# Node1
![Uploading Screenshot 2024-05-30 at 7.22.43 PM.png…]()




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






