# unbound for privacy  

if the AAAA blocking script is used, on modern debian based distributions apparmor needs to be adjusted.  
if you're lazy like me and don't feel the risk of a DNS based attack, you can switch the profile into complain made like so:  
`aa-complain /usr/sbin/unbound`  
