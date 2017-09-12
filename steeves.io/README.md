# steeves.io

New domain, new set of CFN configs to set this up as a cloud service.

##  vpc.cfn.json

JSON config file used to set up VPCs, each with a private and a public subnet.

##  dns.cfn.json

JSON config file used to manage DNS registration for the domain. Currently not sure how to get this to spit out the DNS servers for the HostedZone, may need to ultimately have a bit of shell CLI that does this (or maybe python).
