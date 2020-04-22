# README

FRAMEWORK USED : 
•	Docker: V19.03.0
•	Ruby: 2.5.1
•	Postgresql: 11
•	SQLite: 3.1
•	Nginx


* Deployment instructions

Step1 : Create docker image using the below command
	(docker build -t Dockerfile.rails).
Step2 : Use above image to spin three nodes.
Step3 : Use the ngnix script to enable master and secondary node configuartion(nginx.conf)

Test scripts: startup.sh


Please refer to the attached word document fot additional information on technical details as to why the above frameworks were used and network topology. 
