# Metasploit-Notes

## Basic Syntax

0. reload the Metasploit Framework database ``reload``
1. Run Metasploit : ``msfconsole``
2. Help command   : `` help set ``
3. History command :  ``hestory``
4. Search for exploits : `` search``
5. Select a specific module or exploit : `` use moduleName `` 
6. Set various options for the selected module : `` set ``
7. Unset a previously set option : ``unset``
8. Display various information about the selected module : ``show``
9. Launch the selected exploit or module : ``exploit``
10. Display the list of active sessions : ``sessions``
11. Interact with a specific session ``sessions -i <session_id>``
12. Background the current session and return to the console : ``background``
13. Exit the Metasploit  : ``exit``



## Scanning


### Port Scanning
| Module Path | Description |
| -------- | -------- | 
| auxiliary/scanner/http/wordpress_pingback_access   |  Wordpress Pingback Locator |
| auxiliary/scanner/natpmp/natpmp_portscan           |  NAT-PMP External Port Scanner |
| auxiliary/scanner/portscan/ack                     |  TCP ACK Firewall Scanner |
| auxiliary/scanner/portscan/ftpbounce               |  FTP Bounce Port Scanner |
| auxiliary/scanner/portscan/syn                     |  TCP SYN Port Scanner |
| auxiliary/scanner/portscan/tcp                     |  TCP Port Scanner |
| auxiliary/scanner/portscan/xmas                    |  TCP "XMas" Port Scanner |
| auxiliary/scanner/sap/sap_router_portscanner       |  SAPRouter Port Scanner | 




```
msf6 > search portscan
```

### Service Identification
| Module Path | Description |
| -------- | -------- | 
| auxiliary/scanner/discovery/udp_sweep | Identify services |

### SMB Scanning
| Module Path | Description |
| -------- | -------- | 
| auxiliary/scanner/smb/smb_enumusers           |     SMB User Enumeration (SAM EnumUsers) |
| auxiliary/scanner/smb/smb_version      |     SMB Version Detection |




