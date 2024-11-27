## Browsers in Linux (Docker)

# Install Firefox & Chromium with Docker

This Bash script provides an interactive menu to install Chromium and Firefox browsers using Docker containers.

## Installation

install Chromium and Firefox in Linux

```
bash <(curl -fsSL https://raw.githubusercontent.com/0xs3nat0r/LinuxBrowser/main/utils/installer.sh)
```
## Prerequisite: 
- Docker Auto Installer


Open Chromium :

``
http://<SERVER_IP>:3010
``

``
https://<SERVER_IP>:3011
``

Open Firefox:

``
http://<SERVER_IP>:4010
``

``
https://<SERVER_IP>:4011
``

Note : If the browser window is closed, you can enter the following command in the server:

For Chromium : 
```
docker restart chromium
```
For FireFox : 
```
docker restart firefox
```
