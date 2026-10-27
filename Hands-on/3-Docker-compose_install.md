<div align="center">
<img src=https://static.wixstatic.com/media/1c706c_a5df0ad56f894928bf858a74ba744b32~mv2.png/v1/fit/w_2500,h_1330,al_c/1c706c_a5df0ad56f894928bf858a74ba744b32~mv2.png width="400" height="200">
 </div>

# <div align="center"> DOCKER COMPOSE INSTALL </p>

# <div align="center"> DevOps Instructor-led Training </div>

# <div align="right"> $`\textcolor{brown}{\text{Contact us: }}`$  &emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp; </div>

<div align="right"> T O A C C E L E R A T E Y O U R C A R E E R G R O W T H </div>

### <div align="right"> For questions and more details: </div>

<div align="right"> <img src=https://w7.pngwing.com/pngs/759/922/png-transparent-telephone-logo-iphone-telephone-call-smartphone-phone-electronics-text-trademark-thumbnail.png width="20" height="20"> +91 98712 72900 </div>

<div align="right"> <img src=https://pbs.twimg.com/profile_images/1450734615946219520/jmBHQRRa_400x400.jpg width="20" height="20"> https://www.thecloudtrain.com </div>

<div align="right"> <img src=https://icons.iconarchive.com/icons/martz90/circle/512/email-icon.png width="20" height="20"> support@thecloudtrain.com </div>

<div align="right"> <img src=https://png.pngtree.com/png-vector/20221018/ourmid/pngtree-whatsapp-icon-png-image_6315990.png width="20" height="20"> +91 98712 72900 </div>

## DOCKER COMPOSE INSTALLATION

Refer the [official installation page](https://docs.docker.com/compose/install/linux/).

On Ubuntu 26.04 LTS, Compose v2 is shipped as a **Docker CLI plugin** (`docker compose`).
The old standalone `docker-compose` (v1, Python) binary is end-of-life and must not be used.

### Step 1: If you installed Docker from the official Docker apt repository, the plugin is already available.

If you skipped it earlier, install it with:

`sudo apt update && sudo apt install -y docker-compose-plugin`

### Step 2: Verify the installation.

`docker compose version`

Expected output is similar to `Docker Compose version v2.x.x`.

![image](https://user-images.githubusercontent.com/37858762/235759534-61b4a39e-bd46-48ae-9a94-69155cf98175.png)

### Step 3 (optional): Enable the `docker-compose` alias.

Some older scripts still call `docker-compose`. Ubuntu provides a shim package for that:

`sudo apt install -y docker-compose-v2`

> **Note:** throughout the remaining labs use `docker compose` (with a space), not `docker-compose`.
