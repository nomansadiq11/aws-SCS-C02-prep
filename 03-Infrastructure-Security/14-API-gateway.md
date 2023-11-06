

- We can do real time streaming
- we can manage the version like v1 v2
- we can have dev and prod
- we can have auth
- we can build the api keys
- we can do request throttle if needed
- we can transform invalid requests
- cache api responses

- Integraion
    - Lambda function (rest api backed by lambda function )
    - http onpremise or cloud envirement (we need to leverage the api gateway features )
    - or we can use aws services like step function,
    - We can give access to kinesis data streams via api gateway, than can have KDF
    - you can expose any services outside the api gateway

- You can create private API gateway
- you can identify thee users like IAM roles
- you can use cognito for external users
- customer auth
- you can use the https via https reginal or global


- Advanced
    - we can restric the access for public ip using resouce policy
    - private api only specific network
    - VPC endpoint use to access api other account
    - You can define usage plan
    - you can add throttling plan
