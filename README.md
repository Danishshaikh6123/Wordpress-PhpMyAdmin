
# #Wordpress-PhpMyAdmin

🚀 Here we are going to install Wordpress, Mysql database and Phpmyadmin using docker compose.

🚀 Host the website using Wordpress in dockerize environment.

# Prerequisites

-  Make sure you have AWS account and EC2 created with ubuntu image. 
   
   - [How to create EC2 on AWS.](https://docs.aws.amazon.com/efs/latest/ug/gs-step-one-create-ec2-resources.html) 


-  Install Docker and Docker Compose in Ubuntu.


   - [Install Docker and Docker compose](https://docs.docker.com/engine/install/ubuntu/)

-  You have to open following Ports in security group.

   - Allow 80 to access Wordpress.

   - Allow 8080 to access Phpmyadmin.


## Getting started

- Verify the docker compose version.

     **$ docker-compose --version**

-  Clone this repo to your ubuntu machine to get the source code of this project.   

    **$ git clone** https://github.com/Danishshaikh6123/Wordpress-PhpMyAdmin.git

-  Go to Wordpress-PhpMyAdmin directory.

   **$ cd Wordpress-PhpMyAdmin**

- Now use the below command to create the containers.

   **$ sudo docker-compose up -d**

- Verify the running containers.

  **$ sudo docker ps**  
