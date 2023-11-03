
There are so manay methods

- create new keypair
- update in userdata
- tha simply ssh to ec2
- you cannot delte the existing


2nd
- SSM via the ssm agent
- ssm automation crate key and store private in ssm parameter and public in ec2 instance


3rd
- instnce connect agent
- connect with instance connect agent and edit the ssh keys and add the new keys

4th
- you can use ec2 serial console if you have network issue
-

5th

- you can detach the volumm and attach eto another ec2 instance
- change the keys
- attach back this volumn and try to ssh


Windows ec2 intance keypair

- reattach the ebs and attach to anoterh ec2 windows intance
- than remove the file
- attach atain it will ask you new password


2nd
    - you can do using run command


Ec2 Intance rescue tools

- we have for windows and linux

