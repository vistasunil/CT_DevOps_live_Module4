<div align="center">
<img src=https://static.wixstatic.com/media/1c706c_a5df0ad56f894928bf858a74ba744b32~mv2.png/v1/fit/w_2500,h_1330,al_c/1c706c_a5df0ad56f894928bf858a74ba744b32~mv2.png width="400" height="200">
 </div>

# <div align="center"> DEPLOYING WORDPRESS </p>

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

## DEPLYOING WORDPRESS

### Step 1: Create a folder called **docker-wordpress**

`mkdir docker-wordpress`

`cd docker-wordpress`

![image](https://user-images.githubusercontent.com/37858762/235761596-3d76aadf-aaeb-4867-a674-cdbf3837ed04.png)

### Step 2: Write the sample YAML file in **docker-compose.yml** file

```
version: '3.3'
services:
  db:
    image: mysql:5.7
    volumes:
    - db_data:/var/lib/mysql
    restart: always
    environment:
      MYSQL_ROOT_PASSWORD: somewordpress
      MYSQL_DATABASE: wordpress
      MYSQL_USER: wordpress
      MYSQL_PASSWORD: wordpress
  wordpress:
    depends_on:
    - db
    image: wordpress:latest
    ports:
    - "8000:80"
    restart: always
    environment:
      WORDPRESS_DB_HOST: db:3306
      WORDPRESS_DB_USER: wordpress
      WORDPRESS_DB_PASSWORD: wordpress
volumes:
  db_data:
```
![image](https://user-images.githubusercontent.com/37858762/235761648-abc21d1e-5516-48db-8aaa-f1b70b5069d8.png)

### Step 3: To build this docker-compose file the syntax is the following

`sudo docker-compose up -d`

![image](https://user-images.githubusercontent.com/37858762/235761697-a22a52f6-5cf7-4529-af57-b0efdeee3b32.png)

### Step 4: Ensure all your containers are running.

`sudo docker ps`

### Step 5: Tear down all resources:

`sudo docker-compose down`

![image](https://user-images.githubusercontent.com/37858762/235761817-d4454af9-9441-4b55-9ae2-be7ea2863946.png)

![](RackMultipart20230502-1-20ov17_html_97339f4941a878e6.png
