
- Its backbone of the aws
- allow grant limited to aws resouces
- token valid upto 1 hour
- AssumeRole
    - within your account
    - cross account access: assume role in target account to perform actions there
- AsseumeRoleSAML
    - return creds for the logged using saml
- AssuemroleWebIdentity
    - return crds for users logged with an Ldap
- Getsession token
    - when you doing MFA

<img src="9.1.png" />


- There two version of STS, version 1, 2
    - Regional and global version
    - by default regional enabled



<img src="9.2.png" />


- STS Revoking IAM Role temp
    - if somehow your creds are expose to outside you can add the policy to dened access all TokenIssueTime


<img src="9.3.png" />
