<div align="center">
<img src=https://static.wixstatic.com/media/1c706c_a5df0ad56f894928bf858a74ba744b32~mv2.png/v1/fit/w_2500,h_1330,al_c/1c706c_a5df0ad56f894928bf858a74ba744b32~mv2.png width="400" height="200">
 </div>

# <div align="center"> DOCKER SWARM </p>

# <div align="center"> DevOps Instructor-led Training </div>

<br />

<br />

<br />

<br />

# $${\color{brown} &emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp; Contact&emsp;us: &emsp;&emsp;&emsp; }$$

<div align="right"> T O A C C E L E R A T E Y O U R C A R E E R G R O W T H </div>

### <div align="right"> For questions and more details: </div>

<div align="right"> <img src=https://w7.pngwing.com/pngs/759/922/png-transparent-telephone-logo-iphone-telephone-call-smartphone-phone-electronics-text-trademark-thumbnail.png width="20" height="20"> +91 98712 72900 </div>

<div align="right"> <img src=https://pbs.twimg.com/profile_images/1450734615946219520/jmBHQRRa_400x400.jpg width="20" height="20"> https://www.thecloudtrain.com </div>

<div align="right"> <img src=https://icons.iconarchive.com/icons/martz90/circle/512/email-icon.png width="20" height="20"> support@thecloudtrain.com </div>

<div align="right"> <img src=https://png.pngtree.com/png-vector/20221018/ourmid/pngtree-whatsapp-icon-png-image_6315990.png width="20" height="20"> +91 98712 72900 </div>

## DOCKER SWARM INITIALIZATION

Since we have already installed docker in our system, along with that docker swarm is already installed. We just need to initialize the docker swarm.

### Step 1: Use the following command to create a new swarm.

`sudo docker swarm init --advertise-addr <master IP>`

![image](https://user-images.githubusercontent.com/37858762/235762604-52bb0a07-18c7-4ca8-9def-668a3f538a89.png)

Copy the token to clipboard.

### Step 2: Now we will start a new session as worker, and we will join the swarm that we just created. Paste the copied token shown below.

`sudo <join-command>`

![image](https://user-images.githubusercontent.com/37858762/235762644-03abaea9-f2f1-4f76-a06b-f5c10b9d0018.png)

### Step 3: Now check we will check the node list as the manager.

`sudo docker node ls`

![image](https://user-images.githubusercontent.com/37858762/235762705-98faa497-dc46-417e-8391-c1ea545737d6.png)

As you can see worker has joined and status of both nodes are ready.

### Step 4: Follow the commands given below to leave the swarm.

`sudo docker swarm leave --force`

![image](https://user-images.githubusercontent.com/37858762/235762734-1b033ae2-d31b-4965-99f3-6c40f8a3aca7.png)

Now that the node left the swarm, let's check the node list as manager and check the status of the nodes.

### Step 5: To check the node list as manager follow the command given below.

`sudo docker node ls`

![image](https://user-images.githubusercontent.com/37858762/235762778-aa6e1b43-2b1a-4d64-9a48-c606598b2499.png)

As you can, the status of the node that left the swarm is no longer ready.

### Step 6: To leave the swarm as manager follow the command given below.

`sudo docker swarm leave --force`

![image](https://user-images.githubusercontent.com/37858762/235762818-d5373e1b-c91f-4a4c-a39c-75433916170e.png)
