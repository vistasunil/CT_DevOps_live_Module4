<div align="center">
<img src=https://static.wixstatic.com/media/1c706c_a5df0ad56f894928bf858a74ba744b32~mv2.png/v1/fit/w_2500,h_1330,al_c/1c706c_a5df0ad56f894928bf858a74ba744b32~mv2.png width="400" height="200">
 </div>

# <div align="center"> DOCKER-II ASSIGNMENT </p>

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

## Scenario
**You have been hired as a Devops Engineer in an IT Company. You have been asked to improve the way the company is managing their Docker containers. Following tasks have been assigned:**

### Exercise 1: Bind Mounts

#### Complete below tasks as part of this exercise:**

1. Create a directory **project** in your home directory.
2. Download HTML website source code from [https://www.free-css.com/assets/files/free-css-templates/download/page268/devfolio.zip](https://www.free-css.com/assets/files/free-css-templates/download/page268/devfolio.zip) using **wget** in project folder. Use below command:

`wget https://www.free-css.com/assets/files/free-css-templates/download/page268/devfolio.zip](https://www.free-css.com/assets/files/free-css-templates/download/page268/devfolio.zip`

1. Unzip this devfolio.zip file to project folder using unzip command.
2. Deploy all the HTML website content in any apache container, so that its accessible using public IP. Use bind mount to mount folder devfolio from local host to apache container's /var/www/html folder using bind mounts.
3. Demonstrate how we can dynamically change content in the container by making changes on the host machine

### Exercise 2: Docker Compose

1. Write a docker-compose file to deploy apache and nginx containers using Docker Compose
2. Apache should be exposed on Port 81 and nginx on port 82
3. Demonstrate deployment of these containers using docker compose up
4. Delete altogether using docker compose down

### Exercise 3: Docker Swarm

1. Initialize a Docker Swarm Cluster
2. Create an overlay network
3. Deploy two ubuntu containers in this overlay network.
4. Demonstrate they can communicate with each other, by pinging them. You may need to install iputils-ping in the ubuntu containers to use ping command.
