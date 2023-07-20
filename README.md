#  #Wordpress-PhpMyAdmin
- Here we are hosting website in Wordpress using docker compose.
- In this project we are going to install Wordpress, mysql database and phpmyadmin.

# Project Overview
- Ubuntu based **EC2 instance**.
- 3 docker container using docker compose.
1. Wordpress
2. PhpMyAdmin
3. Mysql

# Getting Started
Steps :-
- Launch EC2 Instance with Ubuntu OS.

- Connect to the instance with SSH.

- Update the packages using below command.

  **$ sudo apt-get update -y**

- Now Install Docker on the server using below command.

  **$ sudo apt-get install docker.io -y**

- Now use below commands to Install docker-compose as we are usining docker compose to create containers at one go.

  **$ sudo curl -L "https://github.com/docker/compose/releases/download/1.29.2/docker-compose-$(uname -s)-$(uname -m)" -o /usr/local/bin/docker-compose**

  **$ sudo chmod +x /usr/local/bin/docker-compose**

- Use the below command to check the docker-compose version.

  **$ docker-compose --version**

- clone this repo to your ubuntu machine to get the source code for this project

  **$ git clone https://github.com/Danishshaikh6123/Wordpress-PhpMyAdmin.git**
  
  NOTE: You can also Fork this repo to get the code in your github repository.

- Go to the **Wordpress-PhpMyAdmin** directory.
   
  **$ cd Wordpress-PhpMyAdmin**

- Now use below command to create the all 3 containers.
  
  **$ sudo docker-compose up -d**

- You should see 3 container running in docker ps.

- You have to open following Ports in security group.
   - update 8000 to access Wordpress webpage.
   - update 3306 to access Mysql Database.
   - update 8080 to access Mysql Database with phpmyadmin GUI interface.


  
  
