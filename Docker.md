# **Docker-Project**
  My first ever project on docker .It's such a greate platform which can be     used by developers for building and     sharing their application fastly .In this     project i have developed a  multi-tier-    architecture system.
---
##  **What is Docker** 
 Docker is a set of platform  as a service (PaaS) products that uses OS-level virtualization to deliver software in packages called containers.Containers are isolated from one another and bundle their own software, libraries and configuration files; they can communicate with each other through well-defined channels.All containers are run by a single operating system kernel and therefore use fewer resources than virtual machines.
 The service has both free and premium tiers. The software that hosts the containers is called Docker Engine
 
![Docker_logo_011](https://user-images.githubusercontent.com/49163207/80633000-b6266e00-8a75-11ea-8fa3-86fd5bd5796a.png)

![continerzation](https://user-images.githubusercontent.com/49163207/80671656-2bbb2a00-8ac8-11ea-8f3d-c1b5bde43c49.png)



### How to setup Docker on Redhat8
These are following steps to setup docker in Redhat OS

    Installation of Redhat in Virtual Box.
![REDHAT](https://user-images.githubusercontent.com/49163207/80632739-5203aa00-8a75-11ea-9160-8bdcb7b1ca78.png)

    Now we need to configure yum in our Redhat base os  by creating DVD repo in it.
![dockerrepo](https://user-images.githubusercontent.com/49163207/80670370-47243600-8ac4-11ea-93fa-c3687b44367d.png)


    We need to create Docker repo file inside yum to install docker .
![docker](https://user-images.githubusercontent.com/49163207/80670567-ddf0f280-8ac4-11ea-9142-e6ecae1f6fd5.png)

     Now run following command to install Docker.
 ![dockerinstall](https://user-images.githubusercontent.com/49163207/80670627-0e389100-8ac5-11ea-9c1f-960250c47b5c.png)
 
    To see version of docker we installed.
![dockerversion](https://user-images.githubusercontent.com/49163207/80670738-52c42c80-8ac5-11ea-9ef0-ce577f03a83f.png)
 
     To start docker.

![dockerstart1](https://user-images.githubusercontent.com/49163207/80671173-b69b2500-8ac6-11ea-97ed-c775a892ae90.png)
     
	 To see status of docker.

![dockerstatus](https://user-images.githubusercontent.com/49163207/80671244-e8ac8700-8ac6-11ea-8cb1-91f5f9def074.png)

    To see all the images inside docker.

![dockerimages](https://user-images.githubusercontent.com/49163207/80671362-332e0380-8ac7-11ea-8d73-ae729027d1f0.png)

    To see all the processes runing inside docker.
![dockerprocesss](https://user-images.githubusercontent.com/49163207/80671451-79836280-8ac7-11ea-8e4a-a9b075c53e02.png)

## Project Related Info

### Joomla

   Joomla is a free and open-source          content  management system (CMS)    for publishing web content,                  developed by Open Source                     Matters,Inc. It is built on a model–         view– controller web application           framework that can be used                  independently of the CMS.

![joomla](https://user-images.githubusercontent.com/49163207/80671982-fcf18380-8ac8-11ea-98f3-ba16dabaaced.png)

![joomlpull](https://user-images.githubusercontent.com/49163207/80672147-84d78d80-8ac9-11ea-886d-b90309f77492.png)


###  MYSQL

  MySQL Database Service is a fully         managed      database service to           deploy cloud-native                               applications   using the world's most    popular open   source database.

![msql](https://user-images.githubusercontent.com/49163207/80672529-b56bf700-8aca-11ea-9df3-b67bec13247d.png)

### Docker Compose
 
 Compose is a tool for defining and running multi-container Docker applications. With Compose, you use a YAML file to configure your application’s services. Then, with a single command, you create and start all the services from your configuration.
 
 ### Steps to create Compose file
 
   Using Compose is basically a three-step process:

    1. Define your app's environment with a Dockerfile so it can be reproduced anywhere.
    2. Define the services that make up your app in  docker-compose.yml so they can be run together in an isolated environment.
    3. Run docker-compose up and Compose starts and runs your entire app.


![docker-compose](https://user-images.githubusercontent.com/49163207/80673083-fa445d80-8acb-11ea-9046-22276ee79568.png)

![docker-compose2](https://user-images.githubusercontent.com/49163207/80673108-11834b00-8acc-11ea-9f7d-8cc0272595ab.png)

To start these services.

![docker-composerun](https://user-images.githubusercontent.com/49163207/80673331-aab26180-8acc-11ea-9e6b-da6c5363da00.png)

To remove these services.

![docker-composedown](https://user-images.githubusercontent.com/49163207/80673538-2b715d80-8acd-11ea-9e44-fcd388d3fd01.png)

Now our services are start we can access this using our  base os ip address  . we can see base os ip uisng this command .

![ifcongi](https://user-images.githubusercontent.com/49163207/80674246-eea66600-8ace-11ea-9057-c1aa4ec66971.png)

![infconfig](https://user-images.githubusercontent.com/49163207/80674304-24e3e580-8acf-11ea-8671-13eb7743c877.png)

### Service Output


![joomlaproject](https://user-images.githubusercontent.com/49163207/80674377-565cb100-8acf-11ea-9f0d-c0a121765714.png)

Thank You

         
 