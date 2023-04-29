# 00 - INSTALL VMS

1. Installed windows server 2022 as a virtual machine in vmware workstation
2.  Installed windows 11 as a virtual machine in vmware workstation


# 01 Installing the Domain Controller

1. Use `sconfig` to :
    - change the hostname
    - change the IP address to static
    - change the DNS server to our own ip address

2. Install the Active Directory Windows Feature

```shell
Install-WindowsFeature AD-Donain-Services -IncludeManangementTools
```
