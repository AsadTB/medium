# Create a new EC2 Instance
- Instance type used: t3.nano
- OS: Ubuntu 22.04 Server
## Things to note
- Public IP
- Security group rules
  - Allow ssh access


# Login with default user
- default user: ubuntu
## Things to note
- (Optional) Add a new entry in /etc/hosts file of local pc to point to your EC2 Instance Public IP


# Create a new user
- user name: abd
- command:


# Create ssh key for the user
- command:
## Things to note
- ssh-keygen
- public and private keys
- Add entry for authorized keys


# Retrieve the private key
- command: scp

# Test the new user login
## Things to note
- chmod permissions for the private key
