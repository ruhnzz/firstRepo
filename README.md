docker username:imruheena18@gmail.com password:Ruheena@18
github username:ruhnzz password:Ruheena@18
jenkins username:Ruheena password:Ruheena@18 port:8080
tomcat username:admin password:1234 port:8083
aws username:imruheena18@gmail.com password:Reema@18  awsacademy.instruture.com

AWS
	Opens the aws academy, select the student login and enter the email and password details 
	Click on Modules
	Scroll down and select Lunch AWS Academy Lab- start Lab
Click on AWS
Click on EC2
Click on Launch Instance
Give name and select ubuntu under application
Click on create-new key pair
Give KeyPair name and click on create key pair
Save the .pem file
In network setting check all the checkboxes oh http and ssh
click on launch instance which is at the bottom right to the page
Wait for the Success message.
Now click on the instances
You have to get 2 tests passes. Now check the box and click on connect.
Copy the path of .pem file that you saved earlier
Open CMD and navigate to that path
Go to SSh and copy the command which is present at the below in aws pate in cmd
Run the command in the terminal and type yes
Run the following commands
sudo apt update
sudo apt-get install docker.io
sudo apt install git similarly nano
Create basic index.html file 
Open git Bash
Run the following commands git init add . commit -m  ''
Create git repo run last 3 commands in git
Clone the repository
cd folder name which we cloned
Write the following data in Dockerfile and click ctrl+o  and ctrl-x
FROM nginx:alpine
COPY ./usr/share/nginx/html
sudo docker build -t mywebapp
sudo docker run -d -p 80:80 mywebapp
copy pulic ip fom aws in instances
paste in browser
sudo docker ps
sudo docker stop cid
instances statesn- terminate
end lab


