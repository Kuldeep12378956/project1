# Project1


## This our client was having Hybrid Infra, 

Where Cloud Flare is the DNS provider. 
All the Servers they have are inhouse. VMware ISXI host.
Applications are hosted on Docker containers inside the VM. 
Jenkins Pipeline Being used for CI/CD
AWS Code Commit used for Virsion Control System & ECR for Container registry. 
They have two environment (Development and Production )

Below are some flow of the work we did for them. 

# Below is the Flow of their traffice being routed to thier applications. 
![singlas flow drawio](https://github.com/Kuldeep12378956/project1/assets/154441092/b12122ed-2777-46ff-a9d1-1f6901af7f6b)


# Below is Flow of how we secured their env variable file using AWS secret manager. 
![secret Manager drawio](https://github.com/Kuldeep12378956/project1/assets/154441092/74ad7452-cc2e-4c7f-b458-26733c4060c6)

# Below is the flow of how their CI CD has been done. 


