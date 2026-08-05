In this project i was able to demonstrate how to create VLANs and assign switch ports on a cisco 2960 switch using Cisco Packet Tracer. 
My network setup: 
1 Cisco switch,
 4 PCs
, VLAN 10 - Admin Department (Ports Fa0/1-2)
, VLAN 20 - Management Department (Ports Fa0/3-4)
, 1 Cisco Router

Main purpose of VLANs is to allow us to logically separate devices into different networks even when they are connected to the same switch. 
After assigning PCs to their respective VLANs, devices within each VLAN can communicate with each other and not outside the VLAN (Devices in VLAN 10 can't communicate with devices in VLAN 20),
i Pinged the devices to verify connectivity within and across the VLANs. With this being done, I lastly added and configured a Cisco router (default gateway) in order to enable communication between devices in different VLANs.
For security purposes i enabled a secret Password on the router.
