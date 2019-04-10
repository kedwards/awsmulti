# awsmultienv

## Dependencies
The following dependenices are required:
 - boto3
 - botocore
 - pbkdf2
 - pycrypto
 
 install by running:
  - pip3 install boto3 botocore pbkdf2 pycrypto

## bringing the CPU over 70%
 - add ssh_key to ssh-agent, for forwarding to the EC2 instances.
 - log into the EC2 instances in the private subnets (via the bastion, portal page will have a ssh command example)
 - run the following command: 
   - stress -c 4