# Linux Diary - Capture The Flag

### **Deployment Guidelines**

1.Create a EC2 Instance on AWS with minimal/required specifications.

2.Install docker and other required tools on the EC2 instance.

3.Make sure the docker images have exposed port 22 and have a ssh service running on it i.e check dockerfile.

4.Create a security group inbound in AWS Console for each port on which ssh on docker container is to be done.

5.Create Elastic IP for instance and accociate it with the instance.

_(Optional)_

6.Assign the Elastic IP to the domain/sub-domain you wish by creating DNS records.


> **Note**: Make sure you terminate and delete everything you created after CTF or else it will charge you for nothing.