# Mini_Project-Linux_Fundamentals

### In this project, I will be executing basic Linux commands on my Linux instance hosted on AWS Cloud services. 
## The tools I will use for this project include:

- GitBash
- Visual Studio Code
- AWS Instance (Ubuntu machine) &
- GitHub

To create an instance on AWS:
To create an instance on AWS:
## Step One (1)
I logged into my AWS account, navigated to EC2, and clicked on `Launch instances`.

![Launching instance](./img/4.awsLaunchInstance.png)

## Step Two (2)
I provided the name of my instance in the `Name` field.

![](./img/5.InstanceName.png)

## Step Three (3)
I chose my key pair from my existing key pairs located in my work directory on my local machine.

![](./img/7.myKeypair.png)

## Step Four (4)
I left the default settings for the `security group`.

![](./img/8.securityGroupDefault.png)

## Step Five (5)
I clicked on `Launch instance`.

![](./img/9.LaunchInstanceAfter.png)

## Step Six (6)
My `instance` is now up and running.

![](./img/10.myInstanceDisplayed.png)

## Step Seven (7)
To connect to my instance, I copied the `Public IP address`.

![](./img/11.publicIPAddress.png)

## Connecting to my Instance using Linux Command on GitBash
## Step One (1)
I navigated (cd) to the directory where I saved my key pair and typed the command `ssh -i mykeypair.pem ubuntu@[the instance public IP address]`.

![](./img/keypair-location-on-dareytraining.png)

## Step Two (2)
I successfully connected to my AWS instance. 

![](./img/connectedToServer.png)


## Basic Linux Commands
Installing, Updating and Removing Software
- Updating Package List
Before installing new software or updating existing package, it's important to refresh the package lists.
![](./img/sudoAptUpdate.png)
![](./img/sudoAptUpdate2.png)

## Installing software Packages
Here I will install a command called `tree` - The `tree` command is commonly used to visually see the file system structure on a Linux server. Below is the command to install it.
![](./img/sudoAptInstall.png)

## To verify installed packages
![](./img/treeConfirm.png)

## Removing software Packages
![](./img/removingPackages.png)


### The above implementation details the steps for setting up and managing a Linux instance on AWS, including how to connect to it and perform basic Linux operations.