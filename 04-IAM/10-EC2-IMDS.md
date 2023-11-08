

- Its ec2 metadata service
- its have key value store in the services
- it useful when automating
- you can get template creds for the role
- all the related to api metadata

- Restrict to IMDS services
    - if you want to restrict the access to metadata you can do local firewall rule
    - if you can turn off from aws cli


- IMDS V1 vs IMDS V2
    - V1
        - its enable by default and you can access the meta data directly
    - V2
        - you need to perform additional step to get the toke to first than you can sent this token to metadata service to get it.

- You can apply scp to all the instances to deny access IMDS 1 api 