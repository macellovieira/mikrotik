The script below allows the setting up of LAN, WAN (direct connect or PPPoE) and, optionally, WLAN. It is entirely driven by variables which are defined in the first part of the script.

A brief description of the functions configured:

Set identity of router

Set password for admin user
Set up NTP client, including adding a script to ensure pool.ntp.org FQDNs are regularly resolved and updated
Set up name servers
Set up WiFi access point and bridge to LAN (optional)
Set up WAN and LAN addressing and default gateway
Set up DHCP server on LAN/WLAN (optional)
Configure NAT on LAN/WLAN (optional)
Set up basic firewall rules
Add and schedule script to ensure mail server FQDN is resolved regularly
Add and schedule script to ensure NTP servers FQDNs are resolved regularly
Add and schedule script to take system backup
Add and schedule script to run on boot to notify of reboot
Add and schedule script to monitor PPPoE connection and restart if we are allocated an address we're not expecting (useful for UK BT based ADSL circuits where BT decide to take over the connection every now and again) (optional)
