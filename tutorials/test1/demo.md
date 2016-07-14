---
title: for demo
description: for demo
tags: [tutorial>www, tutorial>www, tutorial>lll, agreements>Service-Descriptions, tutorial>gateway, semaphore-rejected>SAP-Simple-Finance, tutorial>product>sap-ui5, tutorial>Java-Connector-API-(JCo), agreements>maintenance-/-support-agreements, tutorial>Servlets-/-JSP, tutorial>product>mobile, language>Serbian---Latin, solution>security, agreements>aaa, agreements>general-Terms-&-Conditions, tutorial>ttt, tutorial>new-tag, tutorial>test, tutorial:technology/maven, redirect>types]
qrcode: true
---
TEST   

 ![Image1] (tags.png)
Use Azure PowerShell to [task]  

 ![Image2] (Image 1.png)
 
This article shows you how to [task], using commands from both the Azure module and the Azure Resource Manager module. This is intended to help you learn the new commands as well as migrate existing scripts to the new commands.

## Script  Examples

Here's an example that uses [cmdlet names)] to [task]. It includes commands that:

- [short verb, uses, has, is, etc]
- [next short verb] 

 It includes the following variables: 

- [variable 1]
- [variable 2]
 


190 lines_
```javascript
New-AzureVM –ServiceName $svcname -VMs $vm1 -VNetName $vnetname
$family="Windows Server 2012 R2 Datacenter"
$family="Windows Server 2012 R2 Datacenter"
$image=Get-AzureVMImage | where { $_.ImageFamily -eq $family } | sort PublishedDate -Descending | select -ExpandProperty ImageName -First 1
$image=Get-AzureVMImage | where { $_.ImageFamily -eq $family } | sort PublishedDate -Descending | 
$vmname="AZDC1"
$vmsize="Medium"
$vm1=New-AzureVMConfig -Name $vmname -InstanceSize $vmsize -ImageName $image
$cred=Get-Credential -Message "Type the name and password of the local administrator account."
$vm1 | Add-AzureProvisioningConfig -Windows -AdminUsername $cred.GetNetworkCredential().Username -Password 
$cred.GetNetworkCredential().Password$vm1 | Set-AzureSubnet -SubnetNames "BackEnd"
$vm1 | Set-AzureStaticVNetIP -IPAddress 192.168.244.4
$disksize=20
$disklabel="DCData"
$lun=0
$hcaching="None"
$vm1 | Add-AzureDataDisk -CreateNew -DiskSizeInGB $disksize -DiskLabel $disklabel -LUN $lun -HostCaching $hcaching
$svcname="Azure-TailspinToys"
$vnetname="AZDatacenter"
New-AzureVM –ServiceName $svcname -VMs $vm1 -VNetName $vnetname
$family="Windows Server 2012 R2 Datacenter"
$family="Windows Server 2012 R2 Datacenter"
$image=Get-AzureVMImage | where { $_.ImageFamily -eq $family } | sort PublishedDate -Descending | select -ExpandProperty ImageName -First 1
$image=Get-AzureVMImage | where { $_.ImageFamily -eq $family } | sort PublishedDate -Descending | 
$vmname="AZDC1"
$vmsize="Medium"
$vm1=New-AzureVMConfig -Name $vmname -InstanceSize $vmsize -ImageName $image
$cred=Get-Credential -Message "Type the name and password of the local administrator account."
$vm1 | Add-AzureProvisioningConfig -Windows -AdminUsername $cred.GetNetworkCredential().Username -Password 
$cred.GetNetworkCredential().Password$vm1 | Set-AzureSubnet -SubnetNames "BackEnd"
$vm1 | Set-AzureStaticVNetIP -IPAddress 192.168.244.4
$disksize=20
$disklabel="DCData"
$lun=0
$hcaching="None"
$vm1 | Add-AzureDataDisk -CreateNew -DiskSizeInGB $disksize -DiskLabel $disklabel -LUN $lun -HostCaching $hcaching
$svcname="Azure-TailspinToys"
$vnetname="AZDatacenter"
New-AzureVM –ServiceName $svcname -VMs $vm1 -VNetName $vnetname
$family="Windows Server 2012 R2 Datacenter"
$family="Windows Server 2012 R2 Datacenter"
$image=Get-AzureVMImage | where { $_.ImageFamily -eq $family } | sort PublishedDate -Descending | select -ExpandProperty ImageName -First 1
$image=Get-AzureVMImage | where { $_.ImageFamily -eq $family } | sort PublishedDate -Descending | 
$vmname="AZDC1"
$vmsize="Medium"
$vm1=New-AzureVMConfig -Name $vmname -InstanceSize $vmsize -ImageName $image
$cred=Get-Credential -Message "Type the name and password of the local administrator account."
$vm1 | Add-AzureProvisioningConfig -Windows -AdminUsername $cred.GetNetworkCredential().Username -Password 
$cred.GetNetworkCredential().Password$vm1 | Set-AzureSubnet -SubnetNames "BackEnd"
$vm1 | Set-AzureStaticVNetIP -IPAddress 192.168.244.4
$disksize=20
$disklabel="DCData"
$lun=0
$hcaching="None"
$vm1 | Add-AzureDataDisk -CreateNew -DiskSizeInGB $disksize -DiskLabel $disklabel -LUN $lun -HostCaching $hcaching
$svcname="Azure-TailspinToys"
$vnetname="AZDatacenter"
New-AzureVM –ServiceName $svcname -VMs $vm1 -VNetName $vnetname
$family="Windows Server 2012 R2 Datacenter"
$family="Windows Server 2012 R2 Datacenter"
$image=Get-AzureVMImage | where { $_.ImageFamily -eq $family } | sort PublishedDate -Descending | select -ExpandProperty ImageName -First 1
$image=Get-AzureVMImage | where { $_.ImageFamily -eq $family } | sort PublishedDate -Descending | 
$vmname="AZDC1"
$vmsize="Medium"
$vm1=New-AzureVMConfig -Name $vmname -InstanceSize $vmsize -ImageName $image
$cred=Get-Credential -Message "Type the name and password of the local administrator account."
$vm1 | Add-AzureProvisioningConfig -Windows -AdminUsername $cred.GetNetworkCredential().Username -Password 
$cred.GetNetworkCredential().Password$vm1 | Set-AzureSubnet -SubnetNames "BackEnd"
$vm1 | Set-AzureStaticVNetIP -IPAddress 192.168.244.4
$disksize=20
$disklabel="DCData"
$lun=0
$hcaching="None"
$vm1 | Add-AzureDataDisk -CreateNew -DiskSizeInGB $disksize -DiskLabel $disklabel -LUN $lun -HostCaching $hcaching
$svcname="Azure-TailspinToys"
$vnetname="AZDatacenter"
New-AzureVM –ServiceName $svcname -VMs $vm1 -VNetName $vnetname
$family="Windows Server 2012 R2 Datacenter"
$family="Windows Server 2012 R2 Datacenter"
$image=Get-AzureVMImage | where { $_.ImageFamily -eq $family } | sort PublishedDate -Descending | select -ExpandProperty ImageName -First 1
$image=Get-AzureVMImage | where { $_.ImageFamily -eq $family } | sort PublishedDate -Descending | 
$vmname="AZDC1"
$vmsize="Medium"
$vm1=New-AzureVMConfig -Name $vmname -InstanceSize $vmsize -ImageName $image
$cred=Get-Credential -Message "Type the name and password of the local administrator account."
$vm1 | Add-AzureProvisioningConfig -Windows -AdminUsername $cred.GetNetworkCredential().Username -Password 
$cred.GetNetworkCredential().Password$vm1 | Set-AzureSubnet -SubnetNames "BackEnd"
$vm1 | Set-AzureStaticVNetIP -IPAddress 192.168.244.4
$disksize=20
$disklabel="DCData"
$lun=0
$hcaching="None"
$vm1 | Add-AzureDataDisk -CreateNew -DiskSizeInGB $disksize -DiskLabel $disklabel -LUN $lun -HostCaching $hcaching
$svcname="Azure-TailspinToys"
$vnetname="AZDatacenter"
New-AzureVM –ServiceName $svcname -VMs $vm1 -VNetName $vnetname
$family="Windows Server 2012 R2 Datacenter"
$family="Windows Server 2012 R2 Datacenter"
$image=Get-AzureVMImage | where { $_.ImageFamily -eq $family } | sort PublishedDate -Descending | select -ExpandProperty ImageName -First 1
$image=Get-AzureVMImage | where { $_.ImageFamily -eq $family } | sort PublishedDate -Descending | 
$vmname="AZDC1"
$vmsize="Medium"
$vm1=New-AzureVMConfig -Name $vmname -InstanceSize $vmsize -ImageName $image
$cred=Get-Credential -Message "Type the name and password of the local administrator account."
$vm1 | Add-AzureProvisioningConfig -Windows -AdminUsername $cred.GetNetworkCredential().Username -Password 
$cred.GetNetworkCredential().Password$vm1 | Set-AzureSubnet -SubnetNames "BackEnd"
$vm1 | Set-AzureStaticVNetIP -IPAddress 192.168.244.4
$disksize=20
$disklabel="DCData"
$lun=0
$hcaching="None"
$vm1 | Add-AzureDataDisk -CreateNew -DiskSizeInGB $disksize -DiskLabel $disklabel -LUN $lun -HostCaching $hcaching
$svcname="Azure-TailspinToys"
$vnetname="AZDatacenter"
New-AzureVM –ServiceName $svcname -VMs $vm1 -VNetName $vnetname
$family="Windows Server 2012 R2 Datacenter"
$family="Windows Server 2012 R2 Datacenter"
$image=Get-AzureVMImage | where { $_.ImageFamily -eq $family } | sort PublishedDate -Descending | select -ExpandProperty ImageName -First 1
$image=Get-AzureVMImage | where { $_.ImageFamily -eq $family } | sort PublishedDate -Descending | 
$vmname="AZDC1"
$vmsize="Medium"
$vm1=New-AzureVMConfig -Name $vmname -InstanceSize $vmsize -ImageName $image
$cred=Get-Credential -Message "Type the name and password of the local administrator account."
$vm1 | Add-AzureProvisioningConfig -Windows -AdminUsername $cred.GetNetworkCredential().Username -Password 
$cred.GetNetworkCredential().Password$vm1 | Set-AzureSubnet -SubnetNames "BackEnd"
$vm1 | Set-AzureStaticVNetIP -IPAddress 192.168.244.4
$disksize=20
$disklabel="DCData"
$lun=0
$hcaching="None"
$vm1 | Add-AzureDataDisk -CreateNew -DiskSizeInGB $disksize -DiskLabel $disklabel -LUN $lun -HostCaching $hcaching
$svcname="Azure-TailspinToys"
$vnetname="AZDatacenter"
New-AzureVM –ServiceName $svcname -VMs $vm1 -VNetName $vnetname
$family="Windows Server 2012 R2 Datacenter"
$family="Windows Server 2012 R2 Datacenter"
$image=Get-AzureVMImage | where { $_.ImageFamily -eq $family } | sort PublishedDate -Descending | select -ExpandProperty ImageName -First 1
$image=Get-AzureVMImage | where { $_.ImageFamily -eq $family } | sort PublishedDate -Descending | 
$vmname="AZDC1"
$vmsize="Medium"
$vm1=New-AzureVMConfig -Name $vmname -InstanceSize $vmsize -ImageName $image
$cred=Get-Credential -Message "Type the name and password of the local administrator account."
$vm1 | Add-AzureProvisioningConfig -Windows -AdminUsername $cred.GetNetworkCredential().Username -Password 
$cred.GetNetworkCredential().Password$vm1 | Set-AzureSubnet -SubnetNames "BackEnd"
$vm1 | Set-AzureStaticVNetIP -IPAddress 192.168.244.4
$disksize=20
$disklabel="DCData"
$lun=0
$hcaching="None"
$vm1 | Add-AzureDataDisk -CreateNew -DiskSizeInGB $disksize -DiskLabel $disklabel -LUN $lun -HostCaching $hcaching
$svcname="Azure-TailspinToys"
$vnetname="AZDatacenter"
New-AzureVM –ServiceName $svcname -VMs $vm1 -VNetName $vnetname
$family="Windows Server 2012 R2 Datacenter"
$family="Windows Server 2012 R2 Datacenter"
$image=Get-AzureVMImage | where { $_.ImageFamily -eq $family } | sort PublishedDate -Descending | select -ExpandProperty ImageName -First 1
$image=Get-AzureVMImage | where { $_.ImageFamily -eq $family } | sort PublishedDate -Descending | 
$vmname="AZDC1"
$vmsize="Medium"
$vm1=New-AzureVMConfig -Name $vmname -InstanceSize $vmsize -ImageName $image
$cred=Get-Credential -Message "Type the name and password of the local administrator account."
$vm1 | Add-AzureProvisioningConfig -Windows -AdminUsername $cred.GetNetworkCredential().Username -Password 
$cred.GetNetworkCredential().Password$vm1 | Set-AzureSubnet -SubnetNames "BackEnd"
$vm1 | Set-AzureStaticVNetIP -IPAddress 192.168.244.4
$disksize=20
$disklabel="DCData"
$lun=0
$hcaching="None"
$vm1 | Add-AzureDataDisk -CreateNew -DiskSizeInGB $disksize -DiskLabel $disklabel -LUN $lun -HostCaching $hcaching
$svcname="Azure-TailspinToys"
$vnetname="AZDatacenter"
New-AzureVM –ServiceName $svcname -VMs $vm1 -VNetName $vnetname
$family="Windows Server 2012 R2 Datacenter"
$family="Windows Server 2012 R2 Datacenter"
$image=Get-AzureVMImage | where { $_.ImageFamily -eq $family } | sort PublishedDate -Descending | select -ExpandProperty ImageName -First 1
$image=Get-AzureVMImage | where { $_.ImageFamily -eq $family } | sort PublishedDate -Descending | 
$vmname="AZDC1"
$vmsize="Medium"
$vm1=New-AzureVMConfig -Name $vmname -InstanceSize $vmsize -ImageName $image
$cred=Get-Credential -Message "Type the name and password of the local administrator account."
$vm1 | Add-AzureProvisioningConfig -Windows -AdminUsername $cred.GetNetworkCredential().Username –Password
$image=Get-AzureVMImage | where { $_.ImageFamily -eq $family } | sort PublishedDate -Descending | 
$vmname="AZDC1"
$vmsize="Medium"
$vm1=New-AzureVMConfig -Name $vmname -InstanceSize $vmsize -ImageName $image
$cred=Get-Credential -Message "Type the name and password of the local administrator account."
$vm1 | Add-AzureProvisioningConfig -Windows -AdminUsername $cred.GetNetworkCredential().Username –Password
$image=Get-AzureVMImage | where { $_.ImageFamily -eq $family } | sort PublishedDate -Descending | 
$vmname="AZDC1"
$vmsize="Medium"
``` 
199 lines
```javascript
$vm1 | Set-AzureSubnet -SubnetNames "BackEnd"
$vm1 | Set-AzureStaticVNetIP -IPAddress 192.168.244.4
$disksize=20
$disklabel="DCData"
$lun=0
$hcaching="None"
$vm1 | Add-AzureDataDisk -CreateNew -DiskSizeInGB $disksize -DiskLabel $disklabel -LUN $lun -HostCaching $hcaching
$svcname="Azure-TailspinToys"
$vnetname="AZDatacenter"
New-AzureVM –ServiceName $svcname -VMs $vm1 -VNetName $vnetname
$family="Windows Server 2012 R2 Datacenter"
$family="Windows Server 2012 R2 Datacenter"
$image=Get-AzureVMImage | where { $_.ImageFamily -eq $family } | sort PublishedDate -Descending | select -ExpandProperty ImageName -First 1
$image=Get-AzureVMImage | where { $_.ImageFamily -eq $family } | sort PublishedDate -Descending | 
$vmname="AZDC1"
$vmsize="Medium"
$vm1=New-AzureVMConfig -Name $vmname -InstanceSize $vmsize -ImageName $image
$cred=Get-Credential -Message "Type the name and password of the local administrator account."
$vm1 | Add-AzureProvisioningConfig -Windows -AdminUsername $cred.GetNetworkCredential().Username -Password 
$cred.GetNetworkCredential().Password$vm1 | Set-AzureSubnet -SubnetNames "BackEnd"
$vm1 | Set-AzureStaticVNetIP -IPAddress 192.168.244.4
$disksize=20
$disklabel="DCData"
$lun=0
$hcaching="None"
$vm1 | Add-AzureDataDisk -CreateNew -DiskSizeInGB $disksize -DiskLabel $disklabel -LUN $lun -HostCaching $hcaching
$svcname="Azure-TailspinToys"
$vnetname="AZDatacenter"
New-AzureVM –ServiceName $svcname -VMs $vm1 -VNetName $vnetname
$family="Windows Server 2012 R2 Datacenter"
$family="Windows Server 2012 R2 Datacenter"
$image=Get-AzureVMImage | where { $_.ImageFamily -eq $family } | sort PublishedDate -Descending | select -ExpandProperty ImageName -First 1
$image=Get-AzureVMImage | where { $_.ImageFamily -eq $family } | sort PublishedDate -Descending | 
$vmname="AZDC1"
$vmsize="Medium"
$vm1=New-AzureVMConfig -Name $vmname -InstanceSize $vmsize -ImageName $image
$cred=Get-Credential -Message "Type the name and password of the local administrator account."
$vm1 | Add-AzureProvisioningConfig -Windows -AdminUsername $cred.GetNetworkCredential().Username -Password 
$cred.GetNetworkCredential().Password$vm1 | Set-AzureSubnet -SubnetNames "BackEnd"
$vm1 | Set-AzureStaticVNetIP -IPAddress 192.168.244.4
$disksize=20
$disklabel="DCData"
$lun=0
$hcaching="None"
$vm1 | Add-AzureDataDisk -CreateNew -DiskSizeInGB $disksize -DiskLabel $disklabel -LUN $lun -HostCaching $hcaching
$svcname="Azure-TailspinToys"
$vnetname="AZDatacenter"
New-AzureVM –ServiceName $svcname -VMs $vm1 -VNetName $vnetname
$family="Windows Server 2012 R2 Datacenter"
$family="Windows Server 2012 R2 Datacenter"
$image=Get-AzureVMImage | where { $_.ImageFamily -eq $family } | sort PublishedDate -Descending | select -ExpandProperty ImageName -First 1
$image=Get-AzureVMImage | where { $_.ImageFamily -eq $family } | sort PublishedDate -Descending | 
$vmname="AZDC1"
$vmsize="Medium"
$vm1=New-AzureVMConfig -Name $vmname -InstanceSize $vmsize -ImageName $image
$cred=Get-Credential -Message "Type the name and password of the local administrator account."
$vm1 | Add-AzureProvisioningConfig -Windows -AdminUsername $cred.GetNetworkCredential().Username -Password 
$cred.GetNetworkCredential().Password$vm1 | Set-AzureSubnet -SubnetNames "BackEnd"
$vm1 | Set-AzureStaticVNetIP -IPAddress 192.168.244.4
$disksize=20
$disklabel="DCData"
$lun=0
$hcaching="None"
$vm1 | Add-AzureDataDisk -CreateNew -DiskSizeInGB $disksize -DiskLabel $disklabel -LUN $lun -HostCaching $hcaching
$svcname="Azure-TailspinToys"
$vnetname="AZDatacenter"
New-AzureVM –ServiceName $svcname -VMs $vm1 -VNetName $vnetname
$family="Windows Server 2012 R2 Datacenter"
$family="Windows Server 2012 R2 Datacenter"
$image=Get-AzureVMImage | where { $_.ImageFamily -eq $family } | sort PublishedDate -Descending | select -ExpandProperty ImageName -First 1
$image=Get-AzureVMImage | where { $_.ImageFamily -eq $family } | sort PublishedDate -Descending | 
$vmname="AZDC1"
$vmsize="Medium"
$vm1=New-AzureVMConfig -Name $vmname -InstanceSize $vmsize -ImageName $image
$cred=Get-Credential -Message "Type the name and password of the local administrator account."
$vm1 | Add-AzureProvisioningConfig -Windows -AdminUsername $cred.GetNetworkCredential().Username -Password 
$cred.GetNetworkCredential().Password$vm1 | Set-AzureSubnet -SubnetNames "BackEnd"
$vm1 | Set-AzureStaticVNetIP -IPAddress 192.168.244.4
$disksize=20
$disklabel="DCData"
$lun=0
$hcaching="None"
$vm1 | Add-AzureDataDisk -CreateNew -DiskSizeInGB $disksize -DiskLabel $disklabel -LUN $lun -HostCaching $hcaching
$svcname="Azure-TailspinToys"
$vnetname="AZDatacenter"
New-AzureVM –ServiceName $svcname -VMs $vm1 -VNetName $vnetname
$family="Windows Server 2012 R2 Datacenter"
$family="Windows Server 2012 R2 Datacenter"
$image=Get-AzureVMImage | where { $_.ImageFamily -eq $family } | sort PublishedDate -Descending | select -ExpandProperty ImageName -First 1
$image=Get-AzureVMImage | where { $_.ImageFamily -eq $family } | sort PublishedDate -Descending | 
$vmname="AZDC1"
$vmsize="Medium"
$vm1=New-AzureVMConfig -Name $vmname -InstanceSize $vmsize -ImageName $image
$cred=Get-Credential -Message "Type the name and password of the local administrator account."
$vm1 | Add-AzureProvisioningConfig -Windows -AdminUsername $cred.GetNetworkCredential().Username -Password 
$cred.GetNetworkCredential().Password$vm1 | Set-AzureSubnet -SubnetNames "BackEnd"
$vm1 | Set-AzureStaticVNetIP -IPAddress 192.168.244.4
$disksize=20
$disklabel="DCData"
$lun=0
$hcaching="None"
$vm1 | Add-AzureDataDisk -CreateNew -DiskSizeInGB $disksize -DiskLabel $disklabel -LUN $lun -HostCaching $hcaching
$svcname="Azure-TailspinToys"
$vnetname="AZDatacenter"
New-AzureVM –ServiceName $svcname -VMs $vm1 -VNetName $vnetname
$family="Windows Server 2012 R2 Datacenter"
$family="Windows Server 2012 R2 Datacenter"
$image=Get-AzureVMImage | where { $_.ImageFamily -eq $family } | sort PublishedDate -Descending | select -ExpandProperty ImageName -First 1
$image=Get-AzureVMImage | where { $_.ImageFamily -eq $family } | sort PublishedDate -Descending | 
$vmname="AZDC1"
$vmsize="Medium"
$vm1=New-AzureVMConfig -Name $vmname -InstanceSize $vmsize -ImageName $image
$cred=Get-Credential -Message "Type the name and password of the local administrator account."
$vm1 | Add-AzureProvisioningConfig -Windows -AdminUsername $cred.GetNetworkCredential().Username -Password 
$cred.GetNetworkCredential().Password$vm1 | Set-AzureSubnet -SubnetNames "BackEnd"
$vm1 | Set-AzureStaticVNetIP -IPAddress 192.168.244.4
$disksize=20
$disklabel="DCData"
$lun=0
$hcaching="None"
$vm1 | Add-AzureDataDisk -CreateNew -DiskSizeInGB $disksize -DiskLabel $disklabel -LUN $lun -HostCaching $hcaching
$svcname="Azure-TailspinToys"
$vnetname="AZDatacenter"
New-AzureVM –ServiceName $svcname -VMs $vm1 -VNetName $vnetname
$family="Windows Server 2012 R2 Datacenter"
$family="Windows Server 2012 R2 Datacenter"
$image=Get-AzureVMImage | where { $_.ImageFamily -eq $family } | sort PublishedDate -Descending | select -ExpandProperty ImageName -First 1
$image=Get-AzureVMImage | where { $_.ImageFamily -eq $family } | sort PublishedDate -Descending | 
$vmname="AZDC1"
$vmsize="Medium"
$vm1=New-AzureVMConfig -Name $vmname -InstanceSize $vmsize -ImageName $image
$cred=Get-Credential -Message "Type the name and password of the local administrator account."
$vm1 | Add-AzureProvisioningConfig -Windows -AdminUsername $cred.GetNetworkCredential().Username -Password 
$cred.GetNetworkCredential().Password$vm1 | Set-AzureSubnet -SubnetNames "BackEnd"
$vm1 | Set-AzureStaticVNetIP -IPAddress 192.168.244.4
$disksize=20
$disklabel="DCData"
$lun=0
$hcaching="None"
$vm1 | Add-AzureDataDisk -CreateNew -DiskSizeInGB $disksize -DiskLabel $disklabel -LUN $lun -HostCaching $hcaching
$svcname="Azure-TailspinToys"
$vnetname="AZDatacenter"
New-AzureVM –ServiceName $svcname -VMs $vm1 -VNetName $vnetname
$family="Windows Server 2012 R2 Datacenter"
$family="Windows Server 2012 R2 Datacenter"
$image=Get-AzureVMImage | where { $_.ImageFamily -eq $family } | sort PublishedDate -Descending | select -ExpandProperty ImageName -First 1
$image=Get-AzureVMImage | where { $_.ImageFamily -eq $family } | sort PublishedDate -Descending | 
$vmname="AZDC1"
$vmsize="Medium"
$vm1=New-AzureVMConfig -Name $vmname -InstanceSize $vmsize -ImageName $image
$cred=Get-Credential -Message "Type the name and password of the local administrator account."
$vm1 | Add-AzureProvisioningConfig -Windows -AdminUsername $cred.GetNetworkCredential().Username -Password 
$cred.GetNetworkCredential().Password$vm1 | Set-AzureSubnet -SubnetNames "BackEnd"
$vm1 | Set-AzureStaticVNetIP -IPAddress 192.168.244.4
$disksize=20
$disklabel="DCData"
$lun=0
$hcaching="None"
$vm1 | Add-AzureDataDisk -CreateNew -DiskSizeInGB $disksize -DiskLabel $disklabel -LUN $lun -HostCaching $hcaching
$svcname="Azure-TailspinToys"
$vnetname="AZDatacenter"
New-AzureVM –ServiceName $svcname -VMs $vm1 -VNetName $vnetname
$family="Windows Server 2012 R2 Datacenter"
$family="Windows Server 2012 R2 Datacenter"
$image=Get-AzureVMImage | where { $_.ImageFamily -eq $family } | sort PublishedDate -Descending | select -ExpandProperty ImageName -First 1
$image=Get-AzureVMImage | where { $_.ImageFamily -eq $family } | sort PublishedDate -Descending | 
$vmname="AZDC1"
$vmsize="Medium"
$vm1=New-AzureVMConfig -Name $vmname -InstanceSize $vmsize -ImageName $image
$cred=Get-Credential -Message "Type the name and password of the local administrator account."
$vm1 | Add-AzureProvisioningConfig -Windows -AdminUsername $cred.GetNetworkCredential().Username -Password 
$cred.GetNetworkCredential().Password$vm1 | Set-AzureSubnet -SubnetNames "BackEnd"
$vm1 | Set-AzureStaticVNetIP -IPAddress 192.168.244.4
$disksize=20
$disklabel="DCData"
$lun=0
$hcaching="None"
$vm1 | Add-AzureDataDisk -CreateNew -DiskSizeInGB $disksize -DiskLabel $disklabel -LUN $lun -HostCaching $hcaching
$svcname="Azure-TailspinToys"
$vnetname="AZDatacenter"
New-AzureVM –ServiceName $svcname -VMs $vm1 -VNetName $vnetname
$family="Windows Server 2012 R2 Datacenter"
$family="Windows Server 2012 R2 Datacenter"
$image=Get-AzureVMImage | where { $_.ImageFamily -eq $family } | sort PublishedDate -Descending | select -ExpandProperty ImageName -First 1
$image=Get-AzureVMImage | where { $_.ImageFamily -eq $family } | sort PublishedDate -Descending | 
$vmname="AZDC1"
$vmsize="Medium"
$vm1=New-AzureVMConfig -Name $vmname -InstanceSize $vmsize -ImageName $image
$cred=Get-Credential -Message "Type the name and password of the local administrator account."
$vm1 | Add-AzureProvisioningConfig -Windows -AdminUsername $cred.GetNetworkCredential().Username –Password
$image=Get-AzureVMImage | where { $_.ImageFamily -eq $family } | sort PublishedDate -Descending | 
$vmname="AZDC1"
$vmsize="Medium"
$vm1=New-AzureVMConfig -Name $vmname -InstanceSize $vmsize -ImageName $image
$cred=Get-Credential -Message "Type the name and password of the local administrator account."
$vm1 | Add-AzureProvisioningConfig -Windows -AdminUsername $cred.GetNetworkCredential().Username –Password
$image=Get-AzureVMImage | where { $_.ImageFamily -eq $family } | sort PublishedDate -Descending | 
$vmname="AZDC1"
$vmsize="Medium"
``` 

200 lines
```javascript
$vm1 | Set-AzureSubnet -SubnetNames "BackEnd"
$vm1 | Set-AzureStaticVNetIP -IPAddress 192.168.244.4
$disksize=20
$disklabel="DCData"
$lun=0
$hcaching="None"
$vm1 | Add-AzureDataDisk -CreateNew -DiskSizeInGB $disksize -DiskLabel $disklabel -LUN $lun -HostCaching $hcaching
$svcname="Azure-TailspinToys"
$vnetname="AZDatacenter"
New-AzureVM –ServiceName $svcname -VMs $vm1 -VNetName $vnetname
$family="Windows Server 2012 R2 Datacenter"
$family="Windows Server 2012 R2 Datacenter"
$image=Get-AzureVMImage | where { $_.ImageFamily -eq $family } | sort PublishedDate -Descending | select -ExpandProperty ImageName -First 1
$image=Get-AzureVMImage | where { $_.ImageFamily -eq $family } | sort PublishedDate -Descending | 
$vmname="AZDC1"
$vmsize="Medium"
$vm1=New-AzureVMConfig -Name $vmname -InstanceSize $vmsize -ImageName $image
$cred=Get-Credential -Message "Type the name and password of the local administrator account."
$vm1 | Add-AzureProvisioningConfig -Windows -AdminUsername $cred.GetNetworkCredential().Username -Password 
$cred.GetNetworkCredential().Password$vm1 | Set-AzureSubnet -SubnetNames "BackEnd"
$vm1 | Set-AzureStaticVNetIP -IPAddress 192.168.244.4
$disksize=20
$disklabel="DCData"
$lun=0
$hcaching="None"
$vm1 | Add-AzureDataDisk -CreateNew -DiskSizeInGB $disksize -DiskLabel $disklabel -LUN $lun -HostCaching $hcaching
$svcname="Azure-TailspinToys"
$vnetname="AZDatacenter"
New-AzureVM –ServiceName $svcname -VMs $vm1 -VNetName $vnetname
$family="Windows Server 2012 R2 Datacenter"
$family="Windows Server 2012 R2 Datacenter"
$image=Get-AzureVMImage | where { $_.ImageFamily -eq $family } | sort PublishedDate -Descending | select -ExpandProperty ImageName -First 1
$image=Get-AzureVMImage | where { $_.ImageFamily -eq $family } | sort PublishedDate -Descending | 
$vmname="AZDC1"
$vmsize="Medium"
$vm1=New-AzureVMConfig -Name $vmname -InstanceSize $vmsize -ImageName $image
$cred=Get-Credential -Message "Type the name and password of the local administrator account."
$vm1 | Add-AzureProvisioningConfig -Windows -AdminUsername $cred.GetNetworkCredential().Username -Password 
$cred.GetNetworkCredential().Password$vm1 | Set-AzureSubnet -SubnetNames "BackEnd"
$vm1 | Set-AzureStaticVNetIP -IPAddress 192.168.244.4
$disksize=20
$disklabel="DCData"
$lun=0
$hcaching="None"
$vm1 | Add-AzureDataDisk -CreateNew -DiskSizeInGB $disksize -DiskLabel $disklabel -LUN $lun -HostCaching $hcaching
$svcname="Azure-TailspinToys"
$vnetname="AZDatacenter"
New-AzureVM –ServiceName $svcname -VMs $vm1 -VNetName $vnetname
$family="Windows Server 2012 R2 Datacenter"
$family="Windows Server 2012 R2 Datacenter"
$image=Get-AzureVMImage | where { $_.ImageFamily -eq $family } | sort PublishedDate -Descending | select -ExpandProperty ImageName -First 1
$image=Get-AzureVMImage | where { $_.ImageFamily -eq $family } | sort PublishedDate -Descending | 
$vmname="AZDC1"
$vmsize="Medium"
$vm1=New-AzureVMConfig -Name $vmname -InstanceSize $vmsize -ImageName $image
$cred=Get-Credential -Message "Type the name and password of the local administrator account."
$vm1 | Add-AzureProvisioningConfig -Windows -AdminUsername $cred.GetNetworkCredential().Username -Password 
$cred.GetNetworkCredential().Password$vm1 | Set-AzureSubnet -SubnetNames "BackEnd"
$vm1 | Set-AzureStaticVNetIP -IPAddress 192.168.244.4
$disksize=20
$disklabel="DCData"
$lun=0
$hcaching="None"
$vm1 | Add-AzureDataDisk -CreateNew -DiskSizeInGB $disksize -DiskLabel $disklabel -LUN $lun -HostCaching $hcaching
$svcname="Azure-TailspinToys"
$vnetname="AZDatacenter"
New-AzureVM –ServiceName $svcname -VMs $vm1 -VNetName $vnetname
$family="Windows Server 2012 R2 Datacenter"
$family="Windows Server 2012 R2 Datacenter"
$image=Get-AzureVMImage | where { $_.ImageFamily -eq $family } | sort PublishedDate -Descending | select -ExpandProperty ImageName -First 1
$image=Get-AzureVMImage | where { $_.ImageFamily -eq $family } | sort PublishedDate -Descending | 
$vmname="AZDC1"
$vmsize="Medium"
$vm1=New-AzureVMConfig -Name $vmname -InstanceSize $vmsize -ImageName $image
$cred=Get-Credential -Message "Type the name and password of the local administrator account."
$vm1 | Add-AzureProvisioningConfig -Windows -AdminUsername $cred.GetNetworkCredential().Username -Password 
$cred.GetNetworkCredential().Password$vm1 | Set-AzureSubnet -SubnetNames "BackEnd"
$vm1 | Set-AzureStaticVNetIP -IPAddress 192.168.244.4
$disksize=20
$disklabel="DCData"
$lun=0
$hcaching="None"
$vm1 | Add-AzureDataDisk -CreateNew -DiskSizeInGB $disksize -DiskLabel $disklabel -LUN $lun -HostCaching $hcaching
$svcname="Azure-TailspinToys"
$vnetname="AZDatacenter"
New-AzureVM –ServiceName $svcname -VMs $vm1 -VNetName $vnetname
$family="Windows Server 2012 R2 Datacenter"
$family="Windows Server 2012 R2 Datacenter"
$image=Get-AzureVMImage | where { $_.ImageFamily -eq $family } | sort PublishedDate -Descending | select -ExpandProperty ImageName -First 1
$image=Get-AzureVMImage | where { $_.ImageFamily -eq $family } | sort PublishedDate -Descending | 
$vmname="AZDC1"
$vmsize="Medium"
$vm1=New-AzureVMConfig -Name $vmname -InstanceSize $vmsize -ImageName $image
$cred=Get-Credential -Message "Type the name and password of the local administrator account."
$vm1 | Add-AzureProvisioningConfig -Windows -AdminUsername $cred.GetNetworkCredential().Username -Password 
$cred.GetNetworkCredential().Password$vm1 | Set-AzureSubnet -SubnetNames "BackEnd"
$vm1 | Set-AzureStaticVNetIP -IPAddress 192.168.244.4
$disksize=20
$disklabel="DCData"
$lun=0
$hcaching="None"
$vm1 | Add-AzureDataDisk -CreateNew -DiskSizeInGB $disksize -DiskLabel $disklabel -LUN $lun -HostCaching $hcaching
$svcname="Azure-TailspinToys"
$vnetname="AZDatacenter"
New-AzureVM –ServiceName $svcname -VMs $vm1 -VNetName $vnetname
$family="Windows Server 2012 R2 Datacenter"
$family="Windows Server 2012 R2 Datacenter"
$image=Get-AzureVMImage | where { $_.ImageFamily -eq $family } | sort PublishedDate -Descending | select -ExpandProperty ImageName -First 1
$image=Get-AzureVMImage | where { $_.ImageFamily -eq $family } | sort PublishedDate -Descending | 
$vmname="AZDC1"
$vmsize="Medium"
$vm1=New-AzureVMConfig -Name $vmname -InstanceSize $vmsize -ImageName $image
$cred=Get-Credential -Message "Type the name and password of the local administrator account."
$vm1 | Add-AzureProvisioningConfig -Windows -AdminUsername $cred.GetNetworkCredential().Username -Password 
$cred.GetNetworkCredential().Password$vm1 | Set-AzureSubnet -SubnetNames "BackEnd"
$vm1 | Set-AzureStaticVNetIP -IPAddress 192.168.244.4
$disksize=20
$disklabel="DCData"
$lun=0
$hcaching="None"
$vm1 | Add-AzureDataDisk -CreateNew -DiskSizeInGB $disksize -DiskLabel $disklabel -LUN $lun -HostCaching $hcaching
$svcname="Azure-TailspinToys"
$vnetname="AZDatacenter"
New-AzureVM –ServiceName $svcname -VMs $vm1 -VNetName $vnetname
$family="Windows Server 2012 R2 Datacenter"
$family="Windows Server 2012 R2 Datacenter"
$image=Get-AzureVMImage | where { $_.ImageFamily -eq $family } | sort PublishedDate -Descending | select -ExpandProperty ImageName -First 1
$image=Get-AzureVMImage | where { $_.ImageFamily -eq $family } | sort PublishedDate -Descending | 
$vmname="AZDC1"
$vmsize="Medium"
$vm1=New-AzureVMConfig -Name $vmname -InstanceSize $vmsize -ImageName $image
$cred=Get-Credential -Message "Type the name and password of the local administrator account."
$vm1 | Add-AzureProvisioningConfig -Windows -AdminUsername $cred.GetNetworkCredential().Username -Password 
$cred.GetNetworkCredential().Password$vm1 | Set-AzureSubnet -SubnetNames "BackEnd"
$vm1 | Set-AzureStaticVNetIP -IPAddress 192.168.244.4
$disksize=20
$disklabel="DCData"
$lun=0
$hcaching="None"
$vm1 | Add-AzureDataDisk -CreateNew -DiskSizeInGB $disksize -DiskLabel $disklabel -LUN $lun -HostCaching $hcaching
$svcname="Azure-TailspinToys"
$vnetname="AZDatacenter"
New-AzureVM –ServiceName $svcname -VMs $vm1 -VNetName $vnetname
$family="Windows Server 2012 R2 Datacenter"
$family="Windows Server 2012 R2 Datacenter"
$image=Get-AzureVMImage | where { $_.ImageFamily -eq $family } | sort PublishedDate -Descending | select -ExpandProperty ImageName -First 1
$image=Get-AzureVMImage | where { $_.ImageFamily -eq $family } | sort PublishedDate -Descending | 
$vmname="AZDC1"
$vmsize="Medium"
$vm1=New-AzureVMConfig -Name $vmname -InstanceSize $vmsize -ImageName $image
$cred=Get-Credential -Message "Type the name and password of the local administrator account."
$vm1 | Add-AzureProvisioningConfig -Windows -AdminUsername $cred.GetNetworkCredential().Username -Password 
$cred.GetNetworkCredential().Password$vm1 | Set-AzureSubnet -SubnetNames "BackEnd"
$vm1 | Set-AzureStaticVNetIP -IPAddress 192.168.244.4
$disksize=20
$disklabel="DCData"
$lun=0
$hcaching="None"
$vm1 | Add-AzureDataDisk -CreateNew -DiskSizeInGB $disksize -DiskLabel $disklabel -LUN $lun -HostCaching $hcaching
$svcname="Azure-TailspinToys"
$vnetname="AZDatacenter"
New-AzureVM –ServiceName $svcname -VMs $vm1 -VNetName $vnetname
$family="Windows Server 2012 R2 Datacenter"
$family="Windows Server 2012 R2 Datacenter"
$image=Get-AzureVMImage | where { $_.ImageFamily -eq $family } | sort PublishedDate -Descending | select -ExpandProperty ImageName -First 1
$image=Get-AzureVMImage | where { $_.ImageFamily -eq $family } | sort PublishedDate -Descending | 
$vmname="AZDC1"
$vmsize="Medium"
$vm1=New-AzureVMConfig -Name $vmname -InstanceSize $vmsize -ImageName $image
$cred=Get-Credential -Message "Type the name and password of the local administrator account."
$vm1 | Add-AzureProvisioningConfig -Windows -AdminUsername $cred.GetNetworkCredential().Username -Password 
$cred.GetNetworkCredential().Password$vm1 | Set-AzureSubnet -SubnetNames "BackEnd"
$vm1 | Set-AzureStaticVNetIP -IPAddress 192.168.244.4
$disksize=20
$disklabel="DCData"
$lun=0
$hcaching="None"
$vm1 | Add-AzureDataDisk -CreateNew -DiskSizeInGB $disksize -DiskLabel $disklabel -LUN $lun -HostCaching $hcaching
$svcname="Azure-TailspinToys"
$vnetname="AZDatacenter"
New-AzureVM –ServiceName $svcname -VMs $vm1 -VNetName $vnetname
$family="Windows Server 2012 R2 Datacenter"
$family="Windows Server 2012 R2 Datacenter"
$image=Get-AzureVMImage | where { $_.ImageFamily -eq $family } | sort PublishedDate -Descending | select -ExpandProperty ImageName -First 1
$image=Get-AzureVMImage | where { $_.ImageFamily -eq $family } | sort PublishedDate -Descending | 
$vmname="AZDC1"
$vmsize="Medium"
$vm1=New-AzureVMConfig -Name $vmname -InstanceSize $vmsize -ImageName $image
$cred=Get-Credential -Message "Type the name and password of the local administrator account."
$vm1 | Add-AzureProvisioningConfig -Windows -AdminUsername $cred.GetNetworkCredential().Username –Password
$image=Get-AzureVMImage | where { $_.ImageFamily -eq $family } | sort PublishedDate -Descending | 
$vmname="AZDC1"
$vmsize="Medium"
$vm1=New-AzureVMConfig -Name $vmname -InstanceSize $vmsize -ImageName $image
$cred=Get-Credential -Message "Type the name and password of the local administrator account."
$vm1 | Add-AzureProvisioningConfig -Windows -AdminUsername $cred.GetNetworkCredential().Username –Password
$image=Get-AzureVMImage | where { $_.ImageFamily -eq $family } | sort PublishedDate -Descending | 
$vmname="AZDC1"
$vmsize="Medium"
$vmsize="Medium"
``` 

201 lines
```javascript
$vm1 | Set-AzureSubnet -SubnetNames "BackEnd"
$vm1 | Set-AzureStaticVNetIP -IPAddress 192.168.244.4
$disksize=20
$disklabel="DCData"
$lun=0
$hcaching="None"
$vm1 | Add-AzureDataDisk -CreateNew -DiskSizeInGB $disksize -DiskLabel $disklabel -LUN $lun -HostCaching $hcaching
$svcname="Azure-TailspinToys"
$vnetname="AZDatacenter"
New-AzureVM –ServiceName $svcname -VMs $vm1 -VNetName $vnetname
$family="Windows Server 2012 R2 Datacenter"
$family="Windows Server 2012 R2 Datacenter"
$image=Get-AzureVMImage | where { $_.ImageFamily -eq $family } | sort PublishedDate -Descending | select -ExpandProperty ImageName -First 1
$image=Get-AzureVMImage | where { $_.ImageFamily -eq $family } | sort PublishedDate -Descending | 
$vmname="AZDC1"
$vmsize="Medium"
$vm1=New-AzureVMConfig -Name $vmname -InstanceSize $vmsize -ImageName $image
$cred=Get-Credential -Message "Type the name and password of the local administrator account."
$vm1 | Add-AzureProvisioningConfig -Windows -AdminUsername $cred.GetNetworkCredential().Username -Password 
$cred.GetNetworkCredential().Password$vm1 | Set-AzureSubnet -SubnetNames "BackEnd"
$vm1 | Set-AzureStaticVNetIP -IPAddress 192.168.244.4
$disksize=20
$disklabel="DCData"
$lun=0
$hcaching="None"
$vm1 | Add-AzureDataDisk -CreateNew -DiskSizeInGB $disksize -DiskLabel $disklabel -LUN $lun -HostCaching $hcaching
$svcname="Azure-TailspinToys"
$vnetname="AZDatacenter"
New-AzureVM –ServiceName $svcname -VMs $vm1 -VNetName $vnetname
$family="Windows Server 2012 R2 Datacenter"
$family="Windows Server 2012 R2 Datacenter"
$image=Get-AzureVMImage | where { $_.ImageFamily -eq $family } | sort PublishedDate -Descending | select -ExpandProperty ImageName -First 1
$image=Get-AzureVMImage | where { $_.ImageFamily -eq $family } | sort PublishedDate -Descending | 
$vmname="AZDC1"
$vmsize="Medium"
$vm1=New-AzureVMConfig -Name $vmname -InstanceSize $vmsize -ImageName $image
$cred=Get-Credential -Message "Type the name and password of the local administrator account."
$vm1 | Add-AzureProvisioningConfig -Windows -AdminUsername $cred.GetNetworkCredential().Username -Password 
$cred.GetNetworkCredential().Password$vm1 | Set-AzureSubnet -SubnetNames "BackEnd"
$vm1 | Set-AzureStaticVNetIP -IPAddress 192.168.244.4
$disksize=20
$disklabel="DCData"
$lun=0
$hcaching="None"
$vm1 | Add-AzureDataDisk -CreateNew -DiskSizeInGB $disksize -DiskLabel $disklabel -LUN $lun -HostCaching $hcaching
$svcname="Azure-TailspinToys"
$vnetname="AZDatacenter"
New-AzureVM –ServiceName $svcname -VMs $vm1 -VNetName $vnetname
$family="Windows Server 2012 R2 Datacenter"
$family="Windows Server 2012 R2 Datacenter"
$image=Get-AzureVMImage | where { $_.ImageFamily -eq $family } | sort PublishedDate -Descending | select -ExpandProperty ImageName -First 1
$image=Get-AzureVMImage | where { $_.ImageFamily -eq $family } | sort PublishedDate -Descending | 
$vmname="AZDC1"
$vmsize="Medium"
$vm1=New-AzureVMConfig -Name $vmname -InstanceSize $vmsize -ImageName $image
$cred=Get-Credential -Message "Type the name and password of the local administrator account."
$vm1 | Add-AzureProvisioningConfig -Windows -AdminUsername $cred.GetNetworkCredential().Username -Password 
$cred.GetNetworkCredential().Password$vm1 | Set-AzureSubnet -SubnetNames "BackEnd"
$vm1 | Set-AzureStaticVNetIP -IPAddress 192.168.244.4
$disksize=20
$disklabel="DCData"
$lun=0
$hcaching="None"
$vm1 | Add-AzureDataDisk -CreateNew -DiskSizeInGB $disksize -DiskLabel $disklabel -LUN $lun -HostCaching $hcaching
$svcname="Azure-TailspinToys"
$vnetname="AZDatacenter"
New-AzureVM –ServiceName $svcname -VMs $vm1 -VNetName $vnetname
$family="Windows Server 2012 R2 Datacenter"
$family="Windows Server 2012 R2 Datacenter"
$image=Get-AzureVMImage | where { $_.ImageFamily -eq $family } | sort PublishedDate -Descending | select -ExpandProperty ImageName -First 1
$image=Get-AzureVMImage | where { $_.ImageFamily -eq $family } | sort PublishedDate -Descending | 
$vmname="AZDC1"
$vmsize="Medium"
$vm1=New-AzureVMConfig -Name $vmname -InstanceSize $vmsize -ImageName $image
$cred=Get-Credential -Message "Type the name and password of the local administrator account."
$vm1 | Add-AzureProvisioningConfig -Windows -AdminUsername $cred.GetNetworkCredential().Username -Password 
$cred.GetNetworkCredential().Password$vm1 | Set-AzureSubnet -SubnetNames "BackEnd"
$vm1 | Set-AzureStaticVNetIP -IPAddress 192.168.244.4
$disksize=20
$disklabel="DCData"
$lun=0
$hcaching="None"
$vm1 | Add-AzureDataDisk -CreateNew -DiskSizeInGB $disksize -DiskLabel $disklabel -LUN $lun -HostCaching $hcaching
$svcname="Azure-TailspinToys"
$vnetname="AZDatacenter"
New-AzureVM –ServiceName $svcname -VMs $vm1 -VNetName $vnetname
$family="Windows Server 2012 R2 Datacenter"
$family="Windows Server 2012 R2 Datacenter"
$image=Get-AzureVMImage | where { $_.ImageFamily -eq $family } | sort PublishedDate -Descending | select -ExpandProperty ImageName -First 1
$image=Get-AzureVMImage | where { $_.ImageFamily -eq $family } | sort PublishedDate -Descending | 
$vmname="AZDC1"
$vmsize="Medium"
$vm1=New-AzureVMConfig -Name $vmname -InstanceSize $vmsize -ImageName $image
$cred=Get-Credential -Message "Type the name and password of the local administrator account."
$vm1 | Add-AzureProvisioningConfig -Windows -AdminUsername $cred.GetNetworkCredential().Username -Password 
$cred.GetNetworkCredential().Password$vm1 | Set-AzureSubnet -SubnetNames "BackEnd"
$vm1 | Set-AzureStaticVNetIP -IPAddress 192.168.244.4
$disksize=20
$disklabel="DCData"
$lun=0
$hcaching="None"
$vm1 | Add-AzureDataDisk -CreateNew -DiskSizeInGB $disksize -DiskLabel $disklabel -LUN $lun -HostCaching $hcaching
$svcname="Azure-TailspinToys"
$vnetname="AZDatacenter"
New-AzureVM –ServiceName $svcname -VMs $vm1 -VNetName $vnetname
$family="Windows Server 2012 R2 Datacenter"
$family="Windows Server 2012 R2 Datacenter"
$image=Get-AzureVMImage | where { $_.ImageFamily -eq $family } | sort PublishedDate -Descending | select -ExpandProperty ImageName -First 1
$image=Get-AzureVMImage | where { $_.ImageFamily -eq $family } | sort PublishedDate -Descending | 
$vmname="AZDC1"
$vmsize="Medium"
$vm1=New-AzureVMConfig -Name $vmname -InstanceSize $vmsize -ImageName $image
$cred=Get-Credential -Message "Type the name and password of the local administrator account."
$vm1 | Add-AzureProvisioningConfig -Windows -AdminUsername $cred.GetNetworkCredential().Username -Password 
$cred.GetNetworkCredential().Password$vm1 | Set-AzureSubnet -SubnetNames "BackEnd"
$vm1 | Set-AzureStaticVNetIP -IPAddress 192.168.244.4
$disksize=20
$disklabel="DCData"
$lun=0
$hcaching="None"
$vm1 | Add-AzureDataDisk -CreateNew -DiskSizeInGB $disksize -DiskLabel $disklabel -LUN $lun -HostCaching $hcaching
$svcname="Azure-TailspinToys"
$vnetname="AZDatacenter"
New-AzureVM –ServiceName $svcname -VMs $vm1 -VNetName $vnetname
$family="Windows Server 2012 R2 Datacenter"
$family="Windows Server 2012 R2 Datacenter"
$image=Get-AzureVMImage | where { $_.ImageFamily -eq $family } | sort PublishedDate -Descending | select -ExpandProperty ImageName -First 1
$image=Get-AzureVMImage | where { $_.ImageFamily -eq $family } | sort PublishedDate -Descending | 
$vmname="AZDC1"
$vmsize="Medium"
$vm1=New-AzureVMConfig -Name $vmname -InstanceSize $vmsize -ImageName $image
$cred=Get-Credential -Message "Type the name and password of the local administrator account."
$vm1 | Add-AzureProvisioningConfig -Windows -AdminUsername $cred.GetNetworkCredential().Username -Password 
$cred.GetNetworkCredential().Password$vm1 | Set-AzureSubnet -SubnetNames "BackEnd"
$vm1 | Set-AzureStaticVNetIP -IPAddress 192.168.244.4
$disksize=20
$disklabel="DCData"
$lun=0
$hcaching="None"
$vm1 | Add-AzureDataDisk -CreateNew -DiskSizeInGB $disksize -DiskLabel $disklabel -LUN $lun -HostCaching $hcaching
$svcname="Azure-TailspinToys"
$vnetname="AZDatacenter"
New-AzureVM –ServiceName $svcname -VMs $vm1 -VNetName $vnetname
$family="Windows Server 2012 R2 Datacenter"
$family="Windows Server 2012 R2 Datacenter"
$image=Get-AzureVMImage | where { $_.ImageFamily -eq $family } | sort PublishedDate -Descending | select -ExpandProperty ImageName -First 1
$image=Get-AzureVMImage | where { $_.ImageFamily -eq $family } | sort PublishedDate -Descending | 
$vmname="AZDC1"
$vmsize="Medium"
$vm1=New-AzureVMConfig -Name $vmname -InstanceSize $vmsize -ImageName $image
$cred=Get-Credential -Message "Type the name and password of the local administrator account."
$vm1 | Add-AzureProvisioningConfig -Windows -AdminUsername $cred.GetNetworkCredential().Username -Password 
$cred.GetNetworkCredential().Password$vm1 | Set-AzureSubnet -SubnetNames "BackEnd"
$vm1 | Set-AzureStaticVNetIP -IPAddress 192.168.244.4
$disksize=20
$disklabel="DCData"
$lun=0
$hcaching="None"
$vm1 | Add-AzureDataDisk -CreateNew -DiskSizeInGB $disksize -DiskLabel $disklabel -LUN $lun -HostCaching $hcaching
$svcname="Azure-TailspinToys"
$vnetname="AZDatacenter"
New-AzureVM –ServiceName $svcname -VMs $vm1 -VNetName $vnetname
$family="Windows Server 2012 R2 Datacenter"
$family="Windows Server 2012 R2 Datacenter"
$image=Get-AzureVMImage | where { $_.ImageFamily -eq $family } | sort PublishedDate -Descending | select -ExpandProperty ImageName -First 1
$image=Get-AzureVMImage | where { $_.ImageFamily -eq $family } | sort PublishedDate -Descending | 
$vmname="AZDC1"
$vmsize="Medium"
$vm1=New-AzureVMConfig -Name $vmname -InstanceSize $vmsize -ImageName $image
$cred=Get-Credential -Message "Type the name and password of the local administrator account."
$vm1 | Add-AzureProvisioningConfig -Windows -AdminUsername $cred.GetNetworkCredential().Username -Password 
$cred.GetNetworkCredential().Password$vm1 | Set-AzureSubnet -SubnetNames "BackEnd"
$vm1 | Set-AzureStaticVNetIP -IPAddress 192.168.244.4
$disksize=20
$disklabel="DCData"
$lun=0
$hcaching="None"
$vm1 | Add-AzureDataDisk -CreateNew -DiskSizeInGB $disksize -DiskLabel $disklabel -LUN $lun -HostCaching $hcaching
$svcname="Azure-TailspinToys"
$vnetname="AZDatacenter"
New-AzureVM –ServiceName $svcname -VMs $vm1 -VNetName $vnetname
$family="Windows Server 2012 R2 Datacenter"
$family="Windows Server 2012 R2 Datacenter"
$image=Get-AzureVMImage | where { $_.ImageFamily -eq $family } | sort PublishedDate -Descending | select -ExpandProperty ImageName -First 1
$image=Get-AzureVMImage | where { $_.ImageFamily -eq $family } | sort PublishedDate -Descending | 
$vmname="AZDC1"
$vmsize="Medium"
$vm1=New-AzureVMConfig -Name $vmname -InstanceSize $vmsize -ImageName $image
$cred=Get-Credential -Message "Type the name and password of the local administrator account."
$vm1 | Add-AzureProvisioningConfig -Windows -AdminUsername $cred.GetNetworkCredential().Username –Password
$image=Get-AzureVMImage | where { $_.ImageFamily -eq $family } | sort PublishedDate -Descending | 
$vmname="AZDC1"
$vmsize="Medium"
$vm1=New-AzureVMConfig -Name $vmname -InstanceSize $vmsize -ImageName $image
$cred=Get-Credential -Message "Type the name and password of the local administrator account."
$vm1 | Add-AzureProvisioningConfig -Windows -AdminUsername $cred.GetNetworkCredential().Username –Password
$image=Get-AzureVMImage | where { $_.ImageFamily -eq $family } | sort PublishedDate -Descending | 
$vmname="AZDC1"
$vmsize="Medium"
$vmsize="Medium"
$vmsize="Medium"
``` 


more than 210 lines
```javascript
$vm1 | Set-AzureSubnet -SubnetNames "BackEnd"
$vm1 | Set-AzureStaticVNetIP -IPAddress 192.168.244.4
$disksize=20
$disklabel="DCData"
$lun=0
$hcaching="None"
$vm1 | Add-AzureDataDisk -CreateNew -DiskSizeInGB $disksize -DiskLabel $disklabel -LUN $lun -HostCaching $hcaching
$svcname="Azure-TailspinToys"
$vnetname="AZDatacenter"
New-AzureVM –ServiceName $svcname -VMs $vm1 -VNetName $vnetname
$family="Windows Server 2012 R2 Datacenter"
$family="Windows Server 2012 R2 Datacenter"
$image=Get-AzureVMImage | where { $_.ImageFamily -eq $family } | sort PublishedDate -Descending | select -ExpandProperty ImageName -First 1
$image=Get-AzureVMImage | where { $_.ImageFamily -eq $family } | sort PublishedDate -Descending | 
$vmname="AZDC1"
$vmsize="Medium"
$vm1=New-AzureVMConfig -Name $vmname -InstanceSize $vmsize -ImageName $image
$cred=Get-Credential -Message "Type the name and password of the local administrator account."
$vm1 | Add-AzureProvisioningConfig -Windows -AdminUsername $cred.GetNetworkCredential().Username -Password 
$cred.GetNetworkCredential().Password$vm1 | Set-AzureSubnet -SubnetNames "BackEnd"
$vm1 | Set-AzureStaticVNetIP -IPAddress 192.168.244.4
$disksize=20
$disklabel="DCData"
$lun=0
$hcaching="None"
$vm1 | Add-AzureDataDisk -CreateNew -DiskSizeInGB $disksize -DiskLabel $disklabel -LUN $lun -HostCaching $hcaching
$svcname="Azure-TailspinToys"
$vnetname="AZDatacenter"
New-AzureVM –ServiceName $svcname -VMs $vm1 -VNetName $vnetname
$family="Windows Server 2012 R2 Datacenter"
$family="Windows Server 2012 R2 Datacenter"
$image=Get-AzureVMImage | where { $_.ImageFamily -eq $family } | sort PublishedDate -Descending | select -ExpandProperty ImageName -First 1
$image=Get-AzureVMImage | where { $_.ImageFamily -eq $family } | sort PublishedDate -Descending | 
$vmname="AZDC1"
$vmsize="Medium"
$vm1=New-AzureVMConfig -Name $vmname -InstanceSize $vmsize -ImageName $image
$cred=Get-Credential -Message "Type the name and password of the local administrator account."
$vm1 | Add-AzureProvisioningConfig -Windows -AdminUsername $cred.GetNetworkCredential().Username -Password 
$cred.GetNetworkCredential().Password$vm1 | Set-AzureSubnet -SubnetNames "BackEnd"
$vm1 | Set-AzureStaticVNetIP -IPAddress 192.168.244.4
$disksize=20
$disklabel="DCData"
$lun=0
$hcaching="None"
$vm1 | Add-AzureDataDisk -CreateNew -DiskSizeInGB $disksize -DiskLabel $disklabel -LUN $lun -HostCaching $hcaching
$svcname="Azure-TailspinToys"
$vnetname="AZDatacenter"
New-AzureVM –ServiceName $svcname -VMs $vm1 -VNetName $vnetname
$family="Windows Server 2012 R2 Datacenter"
$family="Windows Server 2012 R2 Datacenter"
$image=Get-AzureVMImage | where { $_.ImageFamily -eq $family } | sort PublishedDate -Descending | select -ExpandProperty ImageName -First 1
$image=Get-AzureVMImage | where { $_.ImageFamily -eq $family } | sort PublishedDate -Descending | 
$vmname="AZDC1"
$vmsize="Medium"
$vm1=New-AzureVMConfig -Name $vmname -InstanceSize $vmsize -ImageName $image
$cred=Get-Credential -Message "Type the name and password of the local administrator account."
$vm1 | Add-AzureProvisioningConfig -Windows -AdminUsername $cred.GetNetworkCredential().Username -Password 
$cred.GetNetworkCredential().Password$vm1 | Set-AzureSubnet -SubnetNames "BackEnd"
$vm1 | Set-AzureStaticVNetIP -IPAddress 192.168.244.4
$disksize=20
$disklabel="DCData"
$lun=0
$hcaching="None"
$vm1 | Add-AzureDataDisk -CreateNew -DiskSizeInGB $disksize -DiskLabel $disklabel -LUN $lun -HostCaching $hcaching
$svcname="Azure-TailspinToys"
$vnetname="AZDatacenter"
New-AzureVM –ServiceName $svcname -VMs $vm1 -VNetName $vnetname
$family="Windows Server 2012 R2 Datacenter"
$family="Windows Server 2012 R2 Datacenter"
$image=Get-AzureVMImage | where { $_.ImageFamily -eq $family } | sort PublishedDate -Descending | select -ExpandProperty ImageName -First 1
$image=Get-AzureVMImage | where { $_.ImageFamily -eq $family } | sort PublishedDate -Descending | 
$vmname="AZDC1"
$vmsize="Medium"
$vm1=New-AzureVMConfig -Name $vmname -InstanceSize $vmsize -ImageName $image
$cred=Get-Credential -Message "Type the name and password of the local administrator account."
$vm1 | Add-AzureProvisioningConfig -Windows -AdminUsername $cred.GetNetworkCredential().Username -Password 
$cred.GetNetworkCredential().Password$vm1 | Set-AzureSubnet -SubnetNames "BackEnd"
$vm1 | Set-AzureStaticVNetIP -IPAddress 192.168.244.4
$disksize=20
$disklabel="DCData"
$lun=0
$hcaching="None"
$vm1 | Add-AzureDataDisk -CreateNew -DiskSizeInGB $disksize -DiskLabel $disklabel -LUN $lun -HostCaching $hcaching
$svcname="Azure-TailspinToys"
$vnetname="AZDatacenter"
New-AzureVM –ServiceName $svcname -VMs $vm1 -VNetName $vnetname
$family="Windows Server 2012 R2 Datacenter"
$family="Windows Server 2012 R2 Datacenter"
$image=Get-AzureVMImage | where { $_.ImageFamily -eq $family } | sort PublishedDate -Descending | select -ExpandProperty ImageName -First 1
$image=Get-AzureVMImage | where { $_.ImageFamily -eq $family } | sort PublishedDate -Descending | 
$vmname="AZDC1"
$vmsize="Medium"
$vm1=New-AzureVMConfig -Name $vmname -InstanceSize $vmsize -ImageName $image
$cred=Get-Credential -Message "Type the name and password of the local administrator account."
$vm1 | Add-AzureProvisioningConfig -Windows -AdminUsername $cred.GetNetworkCredential().Username -Password 
$cred.GetNetworkCredential().Password$vm1 | Set-AzureSubnet -SubnetNames "BackEnd"
$vm1 | Set-AzureStaticVNetIP -IPAddress 192.168.244.4
$disksize=20
$disklabel="DCData"
$lun=0
$hcaching="None"
$vm1 | Add-AzureDataDisk -CreateNew -DiskSizeInGB $disksize -DiskLabel $disklabel -LUN $lun -HostCaching $hcaching
$svcname="Azure-TailspinToys"
$vnetname="AZDatacenter"
New-AzureVM –ServiceName $svcname -VMs $vm1 -VNetName $vnetname
$family="Windows Server 2012 R2 Datacenter"
$family="Windows Server 2012 R2 Datacenter"
$image=Get-AzureVMImage | where { $_.ImageFamily -eq $family } | sort PublishedDate -Descending | select -ExpandProperty ImageName -First 1
$image=Get-AzureVMImage | where { $_.ImageFamily -eq $family } | sort PublishedDate -Descending | 
$vmname="AZDC1"
$vmsize="Medium"
$vm1=New-AzureVMConfig -Name $vmname -InstanceSize $vmsize -ImageName $image
$cred=Get-Credential -Message "Type the name and password of the local administrator account."
$vm1 | Add-AzureProvisioningConfig -Windows -AdminUsername $cred.GetNetworkCredential().Username -Password 
$cred.GetNetworkCredential().Password$vm1 | Set-AzureSubnet -SubnetNames "BackEnd"
$vm1 | Set-AzureStaticVNetIP -IPAddress 192.168.244.4
$disksize=20
$disklabel="DCData"
$lun=0
$hcaching="None"
$vm1 | Add-AzureDataDisk -CreateNew -DiskSizeInGB $disksize -DiskLabel $disklabel -LUN $lun -HostCaching $hcaching
$svcname="Azure-TailspinToys"
$vnetname="AZDatacenter"
New-AzureVM –ServiceName $svcname -VMs $vm1 -VNetName $vnetname
$family="Windows Server 2012 R2 Datacenter"
$family="Windows Server 2012 R2 Datacenter"
$image=Get-AzureVMImage | where { $_.ImageFamily -eq $family } | sort PublishedDate -Descending | select -ExpandProperty ImageName -First 1
$image=Get-AzureVMImage | where { $_.ImageFamily -eq $family } | sort PublishedDate -Descending | 
$vmname="AZDC1"
$vmsize="Medium"
$vm1=New-AzureVMConfig -Name $vmname -InstanceSize $vmsize -ImageName $image
$cred=Get-Credential -Message "Type the name and password of the local administrator account."
$vm1 | Add-AzureProvisioningConfig -Windows -AdminUsername $cred.GetNetworkCredential().Username -Password 
$cred.GetNetworkCredential().Password$vm1 | Set-AzureSubnet -SubnetNames "BackEnd"
$vm1 | Set-AzureStaticVNetIP -IPAddress 192.168.244.4
$disksize=20
$disklabel="DCData"
$lun=0
$hcaching="None"
$vm1 | Add-AzureDataDisk -CreateNew -DiskSizeInGB $disksize -DiskLabel $disklabel -LUN $lun -HostCaching $hcaching
$svcname="Azure-TailspinToys"
$vnetname="AZDatacenter"
New-AzureVM –ServiceName $svcname -VMs $vm1 -VNetName $vnetname
$family="Windows Server 2012 R2 Datacenter"
$family="Windows Server 2012 R2 Datacenter"
$image=Get-AzureVMImage | where { $_.ImageFamily -eq $family } | sort PublishedDate -Descending | select -ExpandProperty ImageName -First 1
$image=Get-AzureVMImage | where { $_.ImageFamily -eq $family } | sort PublishedDate -Descending | 
$vmname="AZDC1"
$vmsize="Medium"
$vm1=New-AzureVMConfig -Name $vmname -InstanceSize $vmsize -ImageName $image
$cred=Get-Credential -Message "Type the name and password of the local administrator account."
$vm1 | Add-AzureProvisioningConfig -Windows -AdminUsername $cred.GetNetworkCredential().Username -Password 
$cred.GetNetworkCredential().Password$vm1 | Set-AzureSubnet -SubnetNames "BackEnd"
$vm1 | Set-AzureStaticVNetIP -IPAddress 192.168.244.4
$disksize=20
$disklabel="DCData"
$lun=0
$hcaching="None"
$vm1 | Add-AzureDataDisk -CreateNew -DiskSizeInGB $disksize -DiskLabel $disklabel -LUN $lun -HostCaching $hcaching
$svcname="Azure-TailspinToys"
$vnetname="AZDatacenter"
New-AzureVM –ServiceName $svcname -VMs $vm1 -VNetName $vnetname
$family="Windows Server 2012 R2 Datacenter"
$family="Windows Server 2012 R2 Datacenter"
$image=Get-AzureVMImage | where { $_.ImageFamily -eq $family } | sort PublishedDate -Descending | select -ExpandProperty ImageName -First 1
$image=Get-AzureVMImage | where { $_.ImageFamily -eq $family } | sort PublishedDate -Descending | 
$vmname="AZDC1"
$vmsize="Medium"
$vm1=New-AzureVMConfig -Name $vmname -InstanceSize $vmsize -ImageName $image
$cred=Get-Credential -Message "Type the name and password of the local administrator account."
$vm1 | Add-AzureProvisioningConfig -Windows -AdminUsername $cred.GetNetworkCredential().Username -Password 
$cred.GetNetworkCredential().Password$vm1 | Set-AzureSubnet -SubnetNames "BackEnd"
$vm1 | Set-AzureStaticVNetIP -IPAddress 192.168.244.4
$disksize=20
$disklabel="DCData"
$lun=0
$hcaching="None"
$vm1 | Add-AzureDataDisk -CreateNew -DiskSizeInGB $disksize -DiskLabel $disklabel -LUN $lun -HostCaching $hcaching
$svcname="Azure-TailspinToys"
$vnetname="AZDatacenter"
New-AzureVM –ServiceName $svcname -VMs $vm1 -VNetName $vnetname
$family="Windows Server 2012 R2 Datacenter"
$family="Windows Server 2012 R2 Datacenter"
$image=Get-AzureVMImage | where { $_.ImageFamily -eq $family } | sort PublishedDate -Descending | select -ExpandProperty ImageName -First 1
$image=Get-AzureVMImage | where { $_.ImageFamily -eq $family } | sort PublishedDate -Descending | 
$vmname="AZDC1"
$vmsize="Medium"
$vm1=New-AzureVMConfig -Name $vmname -InstanceSize $vmsize -ImageName $image
$cred=Get-Credential -Message "Type the name and password of the local administrator account."
$vm1 | Add-AzureProvisioningConfig -Windows -AdminUsername $cred.GetNetworkCredential().Username –Password
$image=Get-AzureVMImage | where { $_.ImageFamily -eq $family } | sort PublishedDate -Descending | 
$vmname="AZDC1"
$vmsize="Medium"
$vm1=New-AzureVMConfig -Name $vmname -InstanceSize $vmsize -ImageName $image
$cred=Get-Credential -Message "Type the name and password of the local administrator account."
$vm1 | Add-AzureProvisioningConfig -Windows -AdminUsername $cred.GetNetworkCredential().Username –Password
$image=Get-AzureVMImage | where { $_.ImageFamily -eq $family } | sort PublishedDate -Descending | 
$vmname="AZDC1"
$vmsize="Medium"
$vmsize="Medium"
$vmsize="Medium"
$hcaching="None"
$vm1 | Add-AzureDataDisk -CreateNew -DiskSizeInGB $disksize -DiskLabel $disklabel -LUN $lun -HostCaching $hcaching
$svcname="Azure-TailspinToys"
$vnetname="AZDatacenter"
New-AzureVM –ServiceName $svcname -VMs $vm1 -VNetName $vnetname
$family="Windows Server 2012 R2 Datacenter"
$family="Windows Server 2012 R2 Datacenter"
$image=Get-AzureVMImage | where { $_.ImageFamily -eq $family } | sort PublishedDate -Descending | select -ExpandProperty ImageName -First 1
$image=Get-AzureVMImage | where { $_.ImageFamily -eq $family } | sort PublishedDate -Descending | 
$vmname="AZDC1"
$vmsize="Medium"
$vm1=New-AzureVMConfig -Name $vmname -InstanceSize $vmsize -ImageName $image
$cred=Get-Credential -Message "Type the name and password of the local administrator account."
$vm1 | Add-AzureProvisioningConfig -Windows -AdminUsername $cred.GetNetworkCredential().Username –Password
$image=Get-AzureVMImage | where { $_.ImageFamily -eq $family } | sort PublishedDate -Descending | 
$vmname="AZDC1"
$vmsize="Medium"
$vm1=New-AzureVMConfig -Name $vmname -InstanceSize $vmsize -ImageName $image
$cred=Get-Credential -Message "Type the name and password of the local administrator account."
$vm1 | Add-AzureProvisioningConfig -Windows -AdminUsername $cred.GetNetworkCredential().Username –Password
$image=Get-AzureVMImage | where { $_.ImageFamily -eq $family } | sort PublishedDate -Descending | 
$vmname="AZDC1"
$vmsize="Medium"
$vmsize="Medium"
```
