# terraform-ansible-roles-roboshop
Creating Roboshop application using terraform and ansible configuration

## Steps
- We have already installed ansible in mongodb instance using remote-exec from bastion instance.
- Which means, got the connection from bastion instance to mongodb
- installed ansible
- clone terraform-ansible-roles-roboshop(this repo) in mongodb instance
- Now call the ansible configuration using play-book commands
- You can find the all the commands in bootstrap.sh in terraform-application-roboshop-dev/40-databases folder
