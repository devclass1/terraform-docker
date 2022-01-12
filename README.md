# terraform-docker
#Install AWS EC2 Amazon-linux2 image and install docker with terraform as follows <br>
yum update -y<br>
amazon-linux-extras install docker<br>
yum install -y yum-utils<br>
yum-config-manager --add-repo https://rpm.releases.hashicorp.com/AmazonLinux/hashicorp.repo<br>
yum -y install terraform<br>
yum install git<br>
service docker start<br>
    
   
