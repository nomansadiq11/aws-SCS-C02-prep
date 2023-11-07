

Microsoft Active Directory

- its database object,
- user, printers, accounts , computers, file shares, security groups
- centrol security mangement
- objects are org by trees
- a group of trees ia forest


- AWS Microsoft Active Directory
    - You will have two AD on premise and cloud, you can mange the users both
    - EC2 windows intances can join domain ad and you can login using ad credentails
    - integration : RDS, SQL, quicksights or thrid party
    - standalone AD
    - its multi-AZ
    - forest trust doesnt means to replicate it but the thing is if one ad doesnt have user than check the other controller to if you have this user

<img src="img/22.1.png " />

<img src="img/22.2.png " />

<img src="img/22.3.png " />

- AD Connectors
    - its proxy
    - no caching
    - users are manage on premise
    - doesnt have inegration with SQL
    - its look basic

<img src="img/22.4.png " />

- SimpleAD
    - inexpensive
    - support joing eec2 machine
    - not rds integation
    - not suport sso
    - small number of users
    - compatible with Microsoft AD
    - no trust between onpremise AD