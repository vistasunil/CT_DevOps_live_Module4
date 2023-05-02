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

## MULTI-TIER APP IN DOCKER SWARM

### Step 1: Create a Docker Network, of type overlay

`docker network create -d overlay my-overlay`

![image](https://user-images.githubusercontent.com/37858762/235768498-28a528c6-e3d0-49ea-a0d0-6d341077b93f.png)

### Step 2: Now, let's create the webapp service

`docker service create --name website --replicas 3 --network my-overlay --publish 80:80 vistasunil/webapp`

![image](https://user-images.githubusercontent.com/37858762/235768520-684f5a5a-8e68-461d-984f-b9872763c817.png)

### Step 3: Let us try running the website in our browser

![image](https://user-images.githubusercontent.com/37858762/235768537-ab02166c-d0a8-4b17-b67d-e3d54de054af.png)

### Step 4: Now, let us deploy the DB service

`docker service create --name db --replicas 1 --network my-overlay vistasunil/mysql:5.6`

![image](https://user-images.githubusercontent.com/37858762/235768555-c3aa5109-1a48-4133-bb82-c89e4e7a5a7c.png)

### Step 5: Let us exec into the db container now, you will have to check on which node the mysql container is present, accordingly do an exec on that container

`docker exec -it <container-id> bash`

![image](https://user-images.githubusercontent.com/37858762/235768578-8be19e77-a568-4b6e-8754-4ec0dc67bfc1.png)

### Step 6: Finally create a my.sql file in this container with the following contents:

```
create database docker;
use docker;
create table emp(name varchar(20), phone varchar(20));
```

![image](https://user-images.githubusercontent.com/37858762/235768594-749912eb-ab6e-4033-890f-750bfea3d6e3.png)

### Step 7: Pass the following command, and this shall build your database and table. The password for mysql is "intelli" and username is "root".

`mysql -u root -p < my.sql`

![image](https://user-images.githubusercontent.com/37858762/235768631-69f83f60-4471-48dc-bce2-fef00f887128.png)

### Step 8: Finally check the website, by entering data, and verifying whether your MySQL table is being populated.

![image](https://user-images.githubusercontent.com/37858762/235768647-949d3568-e9b4-487d-8bc6-030b7be200aa.png)

** Record Created Successfully **

![image](https://user-images.githubusercontent.com/37858762/235768670-2d9f607f-0595-4294-8801-722997ad4406.png)
