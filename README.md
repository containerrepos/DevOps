# Project Title
This project is intended to touch and feel containerized Web Application. 

# Pre-Requisites

Launch ec2 instance to run terraform with name sandbox

Login to sandbox instance

$sudo yum install git -y 

$git clone https://github.com/containerrepos/DevOps.git

$cd DevOps

$sh sandbox.sh

$source export.sh

# Step 1: Build Base AMI
https://github.com/containerrepos/base-ami

# Step 2: Build Custom AMI with Packer
https://github.com/containerrepos/custom-ami.git

# Step 3: Provisioning infrastructure with Terraform
https://github.com/containerrepos/infra-manager

# Step 2: Installing and configuring Jenkins server using Ansible playbook
login to jenkins server 

$sh packages.sh

$sh ssh_keys.sh

$sh play_books.sh


# Step 3: Configure Pipeline project to Build and run containerized Flask app
http://PUBLICIP:8080

a.Intsall docker pipeline and Office 365 connector plugins

b.configure Pipeline project and Microsoft Teams channel

https://github.com/cssp-user/flask-app.git

c.Run the job 

http://PUBLICIP::5001





