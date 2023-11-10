

- Cloudformation
    - its IAC
    - its the way you can create services altoget
    - you can delete all the servics created by CF by deleting the cloufroamtion template


- Cloudformation drift
    - if somebody change resouces from console and called drift

- CF terminate protection
    - if you want to save to accidently terminate, just enable termination protection

- CF Policies
    - We can add the policies to the CF like deny and allow, like deny a resource someone to update

- CF Dynamic Reference
    - you can use storeparameter refeer in cf for secruiet or values
    - you can use secrets managers also
    - dynamic refer
    - secure string
    - secret managers
    - use resolve:secretmanager:mysecre:man

- CF Guard
    - its command cli infromation to validate org policies
    - we can define the polices to validate our cf template if this meets all the requirements
    - we can implement in CICD templates


- CF - AWS service Catalog
    - We can define CF template as product so the user can lanuch those product base on their IAM policy 