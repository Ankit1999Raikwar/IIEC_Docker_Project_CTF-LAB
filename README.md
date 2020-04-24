#   IIEC_Docker_Project MY-personal-CTF-LAB(inside Docker)
   #### Under IIEC-RISE 1.0 Campaign I learnt about Docker under the guidance of Vimal Daga Sir

## Vulnerable web application list
1. juice-shop    
2. bwapp 
3. webgoat-7.0
4. mutillidae
5. web-dvwa
                                     
## What is docker? 
  ****Docker**** is a tool designed to make it easier to ***create, deploy, and run applications*** by using containers. **Containers** allow a developer to package up an application with all of the parts it needs, such as libraries and other dependencies, and deploy it as one package.
   Docker is a bit like a virtual machine. But unlike a virtual machine, rather than creating a whole virtual operating system, Docker allows applications to use the same Linux kernel as the system that they're running on and only requires applications be shipped with things not already running on the host computer. This gives a significant performance boost and reduces the size of the application.
 
 
 ##### Docker  installation 
~~~ sudo apt-get install docker-engine -y
~~~ sudo yum install docker-engine -y
   ##### Start Docker
                      systemctl start Docker
   ##### Stop Docker
                      systemctl stop Docker
   ##### Enable Docker
                      systemctl enable docker
##### Pull Docker images (hub.docker)
                      docker pull bkimminich/juice-shop
##### Push Docker images
                      docker push <imagename> 
##### Run Docker image
                      docker run --rm -p 3000:3000 bkimminich/juice-shop
 "-p " is use for expose port outside the docker image
##### Access the container
         http://localhost:3000
         http://<ip address>:3000
## Docker images links
##### bkimminich/juice-shop (https://hub.docker.com/r/bkimminich/juice-shop)
##### vulnerables/web-dvwa  (https://hub.docker.com/r/vulnerables/web-dvwa)
##### szsecurity/mutillidae (https://hub.docker.com/r/szsecurity/mutillidae)
##### webgoat/webgoat-7.1   (https://hub.docker.com/r/webgoat/webgoat-7.1)
##### raesene/bwapp          (https://hub.docker.com/r/raesene/bwapp)



# Note:-
        this image no support in your docker Engine try with different  version
