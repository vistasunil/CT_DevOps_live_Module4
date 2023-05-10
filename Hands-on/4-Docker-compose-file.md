<div align="center">
<img src=https://static.wixstatic.com/media/1c706c_a5df0ad56f894928bf858a74ba744b32~mv2.png/v1/fit/w_2500,h_1330,al_c/1c706c_a5df0ad56f894928bf858a74ba744b32~mv2.png width="400" height="200">
 </div>

# <div align="center"> DOCKER COMPOSE FILE </p>

# <div align="center"> DevOps Instructor-led Training </div>

# <div align="right"> $`\textcolor{brown}{\text{Contact us: }}`$  &emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp; </div>

<div align="right"> T O A C C E L E R A T E Y O U R C A R E E R G R O W T H </div>

### <div align="right"> For questions and more details: </div>

<div align="right"> <img src=https://w7.pngwing.com/pngs/759/922/png-transparent-telephone-logo-iphone-telephone-call-smartphone-phone-electronics-text-trademark-thumbnail.png width="20" height="20"> +91 98712 72900 </div>

<div align="right"> <img src=https://pbs.twimg.com/profile_images/1450734615946219520/jmBHQRRa_400x400.jpg width="20" height="20"> https://www.thecloudtrain.com </div>

<div align="right"> <img src=https://icons.iconarchive.com/icons/martz90/circle/512/email-icon.png width="20" height="20"> support@thecloudtrain.com </div>

<div align="right"> <img src=https://png.pngtree.com/png-vector/20221018/ourmid/pngtree-whatsapp-icon-png-image_6315990.png width="20" height="20"> +91 98712 72900 </div>

## RUNNING A SAMPLE DOCKER COMPOSE FILE

### Step 1: Create a folder called **docker**

`mkdir docker`

`cd docker`

![image](https://user-images.githubusercontent.com/37858762/235760628-45d2e915-bb77-49bd-81a2-d12a7ccbe79c.png)

### Step 2: Write the sample YAML file in **docker-compose.yml** file

```
version: '3'
services:
  sample1:
    image: httpd
    ports:
    - "5000:5000"
  sample2:
    image: nginx
```

![image](https://user-images.githubusercontent.com/37858762/235760685-09bd221d-7e83-46d3-8dbe-a5e7f4d9b0da.png)

After adding the above content in the .yml file it should look like this:

![image](https://user-images.githubusercontent.com/37858762/235760720-ea3e6f38-56f4-4895-8672-4ce9bd88e937.png)

### Step 3: To build this docker-compose file the syntax is the following:

`docker-compose up -d`

![image](https://user-images.githubusercontent.com/37858762/235760750-481599bb-937a-4c24-9974-7883323ecfc8.png)

### Step 4: Ensure all your containers are running

![image](https://user-images.githubusercontent.com/37858762/235760776-76164aec-6e9a-4c87-9a76-7795db79ecf7.png)

![](RackMultipart20230502-1-vpuih8_html_661b90c4df386c5a.png)
