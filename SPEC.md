## What does this tool does?

It'll scan the scan the netowrk and devices

## What will the tool do with the scans? 
Network: will give you overview of the devices, IP address MAC address and the name of the devices. If the host(the device making the scan, has monitor mode on their Wi-Fi card) then we can act on the unwanted devices.

Port Scans: Tool will gather details from preferred prts, most used ports, or all the ports on the device, and return the user details about those ports.

## 1. MVP
Network scan: This will scan the network for ip addresses and list the ip addresses that are connected to the same network.

- At this stage, only requirement is the list of the online and connected IP, MAC and name of the devices.
- If requested, the output of the previous option can be saved as csv format for future references or comparisons
- Comparison of saved(data from the previous step) or custom IP/MAC addresses or combination of both. 


## 2. MVP
Port Scam: Will scan the ports of desired IP address, and see which ports are open and what services that are running on them. 

- By default scan the first 1024 ports and based on the flags it can select all the ports they want, specify a range or select list of port that user want to scan. 
- Return the service name, version, and if it can be show what kind of connection/requests it acceps. (allowed protocols in http/https for example.)
- Ability to output the results to a file for future references.
