# terraform-docker
#Install AWS EC2 Amazon-linux2 image and install docker with terraform as follows 
yum update -y
amazon-linux-extras install docker
yum install -y yum-utils
yum-config-manager --add-repo https://rpm.releases.hashicorp.com/AmazonLinux/hashicorp.repo
yum -y install terraform
yum install git
service docker start
    
   
