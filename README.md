# Lift and Shift Migration
- "Lift and Shift is a cloud migration strategy where you move an application from an on-premise setting to the cloud with minimal or no modification to its architecture 


## Scenario
- We have application services running on physical or Virtual machines in your Data centre and sometimes you might need various teams working together 

## Problems
- Managing all these services,servers and teams can be complex especially if you want to scale up or down and it might be costly and time consuming
- Most proccesses might be manual and difficult to automate


## Solution
- You can have a Cloud setup where you get all the flexibility and pay as you go and managing infrastructure becomes easier and you can also automate each step


## AWS Services Utilized
- EC2 instances;virtual machine for Tomcat,RabbitMQ,Memcache,MySQL servers
- ELB(load balancer);a replacement of NGINX servers
- AutoScaling;automation for VM scaling ,controls resources and costs
- S3/EFS storage;for shared storage
- Route 53;for private DNS service 


## Sample architecture workflow
![Architecture](https://miro.medium.com/v2/resize:fit:684/1*v486YCZ6Kuh9VZXDWTuKhQ.png)