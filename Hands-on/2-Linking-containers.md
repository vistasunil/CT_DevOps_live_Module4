<div align="center">
<img src=https://static.wixstatic.com/media/1c706c_a5df0ad56f894928bf858a74ba744b32~mv2.png/v1/fit/w_2500,h_1330,al_c/1c706c_a5df0ad56f894928bf858a74ba744b32~mv2.png width="400" height="200">
 </div>

# <div align="center"> LINKING CONTAINERS </p>

# <div align="center"> DevOps Instructor-led Training </div>

# <div align="right"> $`\textcolor{brown}{\text{Contact us: }}`$  &emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp; </div>

<div align="right"> T O A C C E L E R A T E Y O U R C A R E E R G R O W T H </div>

### <div align="right"> For questions and more details: </div>

<div align="right"> <img src=https://w7.pngwing.com/pngs/759/922/png-transparent-telephone-logo-iphone-telephone-call-smartphone-phone-electronics-text-trademark-thumbnail.png width="20" height="20"> +91 98712 72900 </div>

<div align="right"> <img src=https://pbs.twimg.com/profile_images/1450734615946219520/jmBHQRRa_400x400.jpg width="20" height="20"> https://www.thecloudtrain.com </div>

<div align="right"> <img src=https://icons.iconarchive.com/icons/martz90/circle/512/email-icon.png width="20" height="20"> support@thecloudtrain.com </div>

<div align="right"> <img src=https://png.pngtree.com/png-vector/20221018/ourmid/pngtree-whatsapp-icon-png-image_6315990.png width="20" height="20"> +91 98712 72900 </div>

## LINKING CONTAINERS IN DOCKER

### Step 1: Create and Run, two docker containers namely container1 and container2 with Ubuntu image

`docker run –it –name <name-of-container> --link <container-name> -d ubuntu`

![image](https://user-images.githubusercontent.com/37858762/235758412-47bbc772-79d2-48cb-b24d-ccc499e1fcc3.png)

### Step 2: Exec into Container2, and update the container using the following commands:

`docker exec –it <container-name> bash`

`sudo apt-get update`

![image](https://user-images.githubusercontent.com/37858762/235758446-b6ea882a-9b99-482b-bed0-f4ea2db4e120.png)

### Step 3: Now install the ping module on your container2

`apt-get install iputils-ping vim`

![image](https://user-images.githubusercontent.com/37858762/235758481-28af8120-64fd-4258-becb-80dcab1b3afd.png)

### Step 4: Finally, ping container 1 using the following command:

`ping container1`

![image](https://user-images.githubusercontent.com/37858762/235758525-f1e3a7bb-89fd-434c-88fc-5b847dbd0b22.png)
