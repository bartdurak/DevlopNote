- [ ] 
[[samba.canvas|samba]]
[[samba pd]]
[[sudo mount.cifs]]

![[README-20240928214409458.webp]]
 *sudo smbmap -u tid -p Iv.....a -d workgroup -H 192.168.0.210* 
[sudo] password for kli: 

-----------------------------------------------------------------------------
SMBMap - Samba Share Enumerator v1.10.4 | Shawn Evans - ShawnDEvans@gmail.com<mailto:ShawnDEvans@gmail.com>

[\] Checking for open ports...                                                  [*] Detected 1 hosts serving SMB                  
[|] Initializing hosts...                                                       [/] Authenticating...                                                           [-] Authenticating...                                                           [*] Established 1 SMB connections(s) and 1 authenticated session(s)
[\] Authenticating...                                                           [|] Enumerating shares...                                                                                                                                                           
[+] IP: 192.168.0.210:445	Name: 192.168.0.210       	Status: Authenticated
	Disk                                                  	Permissions	Comment
	----                                                  	-----------	-------
free                                              	READ, WRITE	
	ADMIN$                                            	NO ACCESS	Administracja zdalna
	C$                                                	NO ACCESS	Domyślny udział
	G$                                                	NO ACCESS	Domyślny udział
	IPC$                                              	NO ACCESS	Zdalne wywołanie IPC 
	Users                                             	READ ONLY	
[/] Closing connections..                                                       [-] Closing connections..                                                                                                                                       [*] Closed 1 connections
