<html><body><h1 style="font-size:50px;color:blue;">WEZVA TECHNOLOGIES (ADAM) | <font style="color:red;"> www.wezva.com | <font style="color:green;"> +91-9739110917 </h1>
<h1> Subscribe to our youtube channel: 
<a href="https://www.youtube.com/c/DevOpsLearnEasy">https://www.youtube.com/c/DevOpsLearnEasy</a> </h1>
</body></html>


# ANSIBLE ROLES TO SETUP BUILD SERVER FOR SPRINGBOOT AND NODEJS MICROSERVICE

to configure build server for spring boot microservice builds.


ansible-playbook buildsetip.yml -e "springboot=true" -e "awscli=true"

sudo ln -s /opt/awscli-venv/bin/aws /usr/bin/aws

sudo apt install -y ansible

 sudo find / -name "aws"

netstat -tulnp | grep 8080
netstat -an | grep 8080

sudo rm -f /usr/bin/aws
curl "https://awscli.amazonaws.com/awscli-exe-linux-x86_64.zip" -o "awscliv2.zip"
sudo apt update
sudo apt install unzip -y
sudo ./aws/install
which aws
aws --version

After That Test IAM Permission
aws sts get-caller-identity
