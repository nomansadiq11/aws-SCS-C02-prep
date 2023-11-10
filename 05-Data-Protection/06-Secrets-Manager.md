

- AWS Secrets Managers
    - You have better secrets managment in this server from parameter store
    - you rotate force
    - its have integration with aws services
    - secres can be encrypted in KMS
    - Multi-region secrets accross multiple regions

- Advanced
    - You can use KMS to encrypted and decrypt the secrets
    - we can use aws managed key or custom keys
    - all the encyrption happen within the key
    - Rotation
        - you can update automatically
        - update the secrets
        - lamda function can use to automation secrets manager
    - We can ingegrate ECS also, we can inject the secrets in ecs
    - we can define resouces policy for secrets manager
    - 