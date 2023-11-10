

- you can store docker images
- its store by s3
- its support image vulnearbility scanning

- ECR Security
    - You can have integration with KMS they are gooing to encryption using Datakey
    - its use kms:grant
    - image scaning in your container image, basic scanning open-source common vulnerabilities
    - Advance scanning
        - amazon inspact scan continues or automatically
        - inspect will sent evetns to eventbridget than send notification to SNS or lamba
    - cross account
        - you can accessing using policy
    - troubleshooting
        - you may authenticated login to different region
        - maybe you dont have push and pull

- ECS Secrets Manager
    - ECS can inject sensitvie data
    - this can be done using SM or SSM parameteer store

- EKS Concepts
    - manage kubernets cluster on aws
    - Pod evetns, node events
    - keep the history for eks send logs to cloudwatch
    - Control plane
        - send logs to cloudwatch
        - audit logs, diagnostic logs, controller logs
        - ability to select the exact log types to send to CW logs 