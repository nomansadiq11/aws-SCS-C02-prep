

- Direct Connect
    - its dedicated connection between your DC and aws direct connect locations
    - setup virtual private gateway
    - access public resouces privately s3 and ec2
    - increase bandthwithd throuhpu - working with large data set
    - we need to find aws direct connection loation
    - aws direct connect endpoint and custoemr partner router
    - you need to set vif
    - you need to setup virtaul private gateway
    - if you want to connect two vpc in different regio use aws direct connect
    - using private vif use direct connect gateway
    - Connection type
        - Dedicated connection 1GB to 10 GB and 100 GB
            - physical ethernet port dedicated to a customer
            - request made to aws first than completed by aws direct connect partners
        - hosted connections 50 MBps, 500mbps 10 dbps
            - Connection request are made aws direct connect
            - capacity can be added or removed
            - 1, 2, 3, 10 gbps availal at select aws direct connect partners
    - When you have direct connect data is not encrypted but you can add vpn connection IPSec

<img src="img/1.1">


<img src="img/1.2">


- Site to site vpn
    - this can be as backup if the direct connect fails
    