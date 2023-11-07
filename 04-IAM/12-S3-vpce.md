

- S3 vpc gateway no cost
- only resouces in vpc can access
- make sure DNS support enable
- Keep on using public DNS s3
- make sure ec2 outboudn allow for s3


<img src="12.1.png" />



- VPC interface endpont for s3
- ENI deployed subnet
- can access from onpremise or vpn
- the publick hostname will resolve thee private interface
- both vpc setting enables DNS and Hostnames
- there is not private dns name, the traffic will route internall


<img src="12.2.png" />

<img src="12.3.png" />



- you can resric by source vpc and vpce
- sourceip for public
- sourcevpc for privates ips
- 