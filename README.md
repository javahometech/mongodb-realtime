# Install Ansible on Amazon Linux

```
  sudo yum install epel-release -y
  sudo yum install ansible -y
```

# Setting up password less communication from Jenkins to other servers
Become Jenkins user
```
  sudo su -s /bin/bash jenkins
```

Generate public/private key pair
```
  ssh-keygen
```
