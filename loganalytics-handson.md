# arm-sample
Azure ARM Template Sample

## リソースの展開
[![Deploy to Azure](https://aka.ms/deploytoazurebutton)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fh-morozumi%2Farm-sample%2Fmain%2F02_VMdeploy_ARMtemplate.json)

## パラメータ
- **Virtual Network Name**:	仮想ネットワーク名(AzureStudy-vnet)
- **Virtual Network Address Prefix**:	IPv4 アドレス空間(172.0.0.0/24)
- **Windows Virtual Machine Subnet Name**:	サブネット名(Windows-VM-subnet)
- **Windows Virtual Machine Subnet Prefix**:	サブネット アドレス範囲(172.0.0.0/26)
- **Windows Virtual Machine Subnet NSG Name**:	ネットワークセキュリティグループ(Windows-VM-nsg)
- **Windows Admin User Name**:	ローカル管理者
- **Windows Admin Password**:	パスワード
- **Windows OS Version**:	WindowsOSイメージ(2016-Datacenter)
- **Windows Virtual Machine Size**:	Windows仮想マシンサイズ(Standard_D2_v3)
- **Windows Virtual Machine NIC**:	Windows仮想マシンNIC(Windows-VM-nic)
- **Windows Virtual Machine Name**:	Windows仮想マシン名(Windows-VM)
- **Windows Managed Disk Type**:	Windowsディスクタイプ(StandardSSD_LRS)
- **Linux Virtual Machine Subnet Name**:	サブネット名(Linux-VM-subnet)
- **Linux Virtual Machine Subnet Prefix**:	サブネット アドレス範囲(172.0.0.64/26)
- **Linux Virtual Machine Subnet NSG Name**:	ネットワークセキュリティグループ(Linux-VM-nsg)
- **Linux Admin User Name**:	ローカル管理者
- **Linux Admin Password**:	パスワード
- **Ubuntu OS Version**:	LinuxOSイメージ(18.04-LTS)
- **Linux Virtual Machine Size**:	Linux仮想マシンサイズ(Standard_D2_v3)
- **Linux Virtual Machine NIC**:	Linux仮想マシンNIC(Linux-VM-nic)
- **Linux Virtual Machine Name**:	Linux仮想マシン名(Linux-VM)
- **Linux Managed Disk Type**:	Linuxディスクタイプ(StandardSSD_LRS)
- **Azure Bastion Subnet Name**:	踏み台サブネット名(AzureBastionSubnet)
- **Azure Bastion Subnet Prefix**:	踏み台サブネット アドレス範囲(172.0.0.128/26)
- **Azure Bastion Host Name**:	踏み台ホスト名(AzureBastionHost)
- **Azure Bastion Public IP**:	踏み台パブリックIP(AzureBastion-pip)