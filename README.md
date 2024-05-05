# Project1


## This our client was having Hybrid Infra, 

Where Cloud Flare is the DNS provider. 
All the Servers they have are inhouse. VMware ISXI host.
Applications are hosted on Docker containers inside the VM. 
Jenkins Pipeline Being used for CI/CD
AWS Code Commit used for Virsion Control System & ECR for Container registry. 
They have two environment (Development and Production )

Below are some flow of the work we did for them. 

## Below is the Flow of their traffice being routed to thier applications. 
![singlas flow drawio](https://github.com/Kuldeep12378956/project1/assets/154441092/b12122ed-2777-46ff-a9d1-1f6901af7f6b)


## Below is Flow of how we secured their env variable file using AWS secret manager. 
![secret Manager drawio](https://github.com/Kuldeep12378956/project1/assets/154441092/74ad7452-cc2e-4c7f-b458-26733c4060c6)

## We streamlined there user Management using SSO & RBAC. 
![UserManagemet-Workflow](https://github.com/Kuldeep12378956/project1/assets/154441092/bca1b59f-a70a-4d43-881c-637043262200)

## We set the notification for any new commit in code Commit. 

![codecommit notification](https://github.com/Kuldeep12378956/project1/assets/154441092/68a164f5-d877-4e76-a3fa-9008dc2788b2)


## We streamlined their Database Work Flow.

### Before it was like :-

![Dev Backup and Production restoration ](https://github.com/Kuldeep12378956/project1/assets/154441092/24ea36ef-9a01-4898-b90d-df88269c345f)

### Our Planning :- 
![Dev and Prod Database workflow architect drawio (2)](https://github.com/Kuldeep12378956/project1/assets/154441092/60e9c1af-ce91-499a-9911-753b142f8fde)

### Implimentation :- 
![diagram drawio](https://github.com/Kuldeep12378956/project1/assets/154441092/3591ef8c-ba35-4d1d-a598-b7fce9f647c9)













