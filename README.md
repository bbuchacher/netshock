# netshock
## About
This module utilzies the shellshock vulnerability on many home and enterprise netgear routers. 
I will not be supplying the vulnerable pages, just the module itself and payload. I have submitted this to the metasploit repo but we will see if it makes it in.. 
Cheers, and happy hacking... 
## Usage 
Copy the module into your metasploit directory, 

SET RHOST = {Vulnerable Netgear Infrastructure" 
SET RPORT = {Port That vulnerable product is listening on " 
SET LHOST = {The IP For Connect Back}
SET URI = {The Vulnerable Page}
exploit -j 

### POC 



