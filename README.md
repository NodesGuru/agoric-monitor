[![Nodes.Guru Logo](https://api.nodes.guru/nodesguru_wide.png "Nodes.Guru Logo")](https://nodes.guru "Nodes.Guru")
# Agoric Monitor
Rainmeter extension for Agoric node monitoring.

![Widget Preview](https://github.com/NodesGuru/agoric-monitor/raw/main/%40Resources/v1.1.png)

# Requirements
 * Enabled 26660 port on your node (you can follow [this guide](https://nodes.guru/agoric/setup-guide/en) to do that)
 * [Rainmeter ](https://www.rainmeter.net)
 
### Features:
 * Node status (online/offline)
 * Current validator height
 * Current network height
 * Missed blocks for your validator
 * Your validator power
 * Count of validators (overall)
 * Size of mempool
 * Number of transactions in network
 * Number of connected peers
 * Latest version from [Agoric repo](https://github.com/Agoric/agoric-sdk)
 * CPU, RAM and Disk usage monitor (**v1.1**)

# Installation
### On server side:
 1. Execute the following:  
 ```wget -q -O guru_exporter.sh https://api.nodes.guru/guru_exporter.sh && chmod +x guru_exporter.sh && sudo /bin/bash guru_exporter.sh```
### On client side:
 1. Download latest [release](https://github.com/NodesGuru/agoric-monitor/releases/latest)
 2. Install [Rainmeter](https://www.rainmeter.net).
 3. Install Agoric.Node.Monitor_\*.rmskin
 4. Change IP address in agoric.ini from 0.0.0.0 to your node IP
 5. Refresh again
 6. Vous à la!
