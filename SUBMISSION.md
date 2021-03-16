James Trieu 1151746

# Deliverables [50 pts]

## DOCKER
- [5 pts] Your dockerfile. Please provide a link to this file rather than a screen capture.
>- [Dockerfile](Dockerfile)
- [5 pts] Your running docker instance as shown by a ps command.
![docker instance](images/docker_instance.png)
- [5 pts] Your browser accessing the main page of the website from your local container.
![website main](images/docker_website.png)

## DOCKER COMPOSE - MYSQL ONLY
- [5 pts] The output from the docker-compose up command.
![docker up mysql](images/docker_up1.png)
- [5 pts] Your browser accessing the "Veterinarians" page of the website from your local container when you run the application from the host system.
![website veterinarians #1](images/docker_website-vet1.png)
- [5 pts] A section of the stack trace generated when you attempt to run the application container that has been updated to use MySQL.
![docker mysql stack](images/docker_stack.png)

## DOCKER COMPOSE - APP SERVER & MYSQL
- [5 pts] Your updated docker-compose.yml file containing the application serer, built from your local Dockerfile, and the existing MySQL configuration. Please provide a link to this file rather than a screen capture.
>- [docker-compose.yml](docker-compose.yml)
- [5 pts] Your updated application-mysql.properties file containing the URL change for the database server. Please provide a link to this file rather than a screen capture.
>- [application-mysql.properties](\src\main\resources\application-mysql.properties)
- [5 pts] The output from the docker-compose up command.
![docker up server](images/docker_up2.png)
- [5 pts] Your browser accessing the "Veterinarians" page of the website from your local container.
![website veterinarians #2](images/docker_website-vet2.png)