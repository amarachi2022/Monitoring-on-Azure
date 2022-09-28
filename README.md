# Monitoring-on-Azure
## Queried logs on a Virtual Machine using Log analytics workspace.

### Task 1: Deployed an Azure virtual machine using this code snippet on Cloud Shell

```
New-AzVm -ResourceGroupName "AZ500LAB131415" -Name "myVM" -Location 'EastUS' -VirtualNetworkName "myVnet" -SubnetName "mySubnet" -SecurityGroupName   "myNetworkSecurityGroup" -PublicIpAddressName "myPublicIpAddress" -OpenPorts 80,3389 
```

### Task 2: Created a Log Analytics workspace in US East with Azure Portal and enabled the Log Analytics virtual machine extension to collect data from the VM and transfer it to the workspace

<img width="960" alt="vm connected to log" src="https://user-images.githubusercontent.com/110430121/192772330-e0bfdbff-a42a-4267-8a55-331c8af38bbe.png">

### Task 3: Collected virtual machine event and performance data in the Log analytics Workspace

<img width="960" alt="agents applied" src="https://user-images.githubusercontent.com/110430121/192772626-562ae8cd-999b-4427-a2ee-80b1947e5bb0.png">

### Task 4: View and query collected data

<img width="960" alt="run query" src="https://user-images.githubusercontent.com/110430121/192771994-83e26d59-ecb6-4184-8002-67913f5b7cb1.png">
