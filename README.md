# Deploy
Deploy Nodejs App on AWS
#########
#autor :Rishikesh
#Reference :Kunal Verma
#version: demo
##########
# Steps to run on local machine
1.Clone the repo from (https://github.com/verma-kunal/AWS-Session?tab=readme-ov-file) to your local machine
2.create a hidden file .env (enviorment variable for stripe payment API ID )
{
DOMAIN= ""
PORT=3000
STATIC_DIR="./client"

PUBLISHABLE_KEY=""
SECRET_KEY=""
}
3.install NPM ( npm install)
4.run the node js server (NPM run start)

# Steps to run on AWS
1.Create a new userfrom IAM (good practice )
2.Add policy (administrator access)
3.Create a ec2 instance 
4.Connect it with ssh (or connect to instance as per your prefrence)
5.install git on ec2
6.install nodejs /install NPM
7.Go to EC2>instance select the instance 
8.go to security >inbond rules 
9. add a inbond rule on port 3000 to be access on local internet 
10. go to browser enter the public IP for ec2:3000 




