# PS_lan_dev_res
Power Shell code for resource info collection from device in local network 
This script will use the Get-WmiObject cmdlet to collect information about the CPU, memory, and disk of each computer on the LAN. The information is stored in an array of objects, and the script uses the Format-Table cmdlet to display the information in a tabular format.

It will read list of computer names from text file located in C:\computerlist.txt.
You need to make sure that you have enough permission to access resources of computers, and also your computer has to be in the same domain as target machines.
Also by default it will only check C: drive for disk usage, if you want to check other drive you can add them and name them as DeviceID='D:' for D drive and so on

Please note that this script is provided for educational purposes and should be used with caution in production environments, as it can potentially cause a large amount of network traffic.



