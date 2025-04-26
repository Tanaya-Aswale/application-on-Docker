# Hosted AGE-CALCULATOR Application on Docker Container using AWS

# install git on ec2 instance

sudo yum install git -y 

# install docker on ec2

sudo yum update -y<br>
sudo yum install docker -y<br>
sudo service docker start<br>
sudo usermod -a -G docker ec2-user<br>

# Clone the app on ec2 using Git

git clone (link)

# Build and Run Docker Container

docker build -t app .<br>
docker run -d -p 80:80 app <br>

## Add the security group rules based on port mapping

# ALL the best 
