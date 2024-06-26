To Do
AWS VPC Exercise
Task
Create a VPC

![](https://github.com/Visemir/homework14/blob/main/createvpc.jpg)

Create two subnet groups: public and private

![](https://github.com/Visemir/homework14/blob/main/publicsubnet.jpg)
![](https://github.com/Visemir/homework14/blob/main/privatsubnet.jpg)
![](https://github.com/Visemir/homework14/blob/main/publicsubnetroute.jpg)
![](https://github.com/Visemir/homework14/blob/main/privatsubnetroute.jpg)
Create one EC2 instance in the public subnet and one EC2 instance in the private subnet
Ensure that the EC2 instance in the public subnet is accessible over the internet, allowing you to connect via SSH

![](https://github.com/Visemir/homework14/blob/main/publicinstansnet.jpg)

Ensure that the EC2 instance in the private subnet is not accessible from the internet but is accessible from the EC2 instance in the public subnet
Ensure that the EC2 instance in the private subnet has access to the internet

![](https://github.com/Visemir/homework14/blob/main/privatinstansnet.jpg)
