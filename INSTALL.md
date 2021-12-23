# Getting Started

### Microservice to send mail
---
#### Steps to build
- Build:  ```mvn clean package -DskipTests```
- Go to the [Postgres Container Folder](https://github.com/mateusesp/ms-email/tree/master/postgresContainer) and run ```docker-compose up -d```
- To see if container is running: ```docker ps -a```
- change the [application.yml](https://github.com/mateusesp/ms-email/blob/master/src/main/resources/application.yml) with your e-mail info
---
#### Sending an e-mail
-  When you go to run the application, you need to set two environment variables: ```GMAIL_PASSWORD``` and ```GMAIL_USERNAME``` with your credentials   
  
-  Your ```GMAIL_PASSWORD``` can be created here: [Gmail 16 Characters Password](https://support.google.com/accounts/answer/185833)

-  You can find a example to see how you can send an e-mail in: [Postman Collection](https://github.com/mateusesp/ms-email/blob/master/Collection/Microservice%20Email.postman_collection.json)
  
---
