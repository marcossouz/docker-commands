<h1 align="center"> Docker commands </h1>

<p align="center"> Repository created for docker build scripts </p>

# Content

> create container postgres 
> - `sudo docker run --name postgres -p 5432:5432 -v postgresl-data:/var/lib/postgresql/data -e POSTGRES_PASSWORD=mypass --restart always -d postgres:latest` 

> create container elasticsearch
> - `sudo docker run -d --name elasticsearch -p 9200:9200 -p 9300:9300 -e "discovery.type=single-node" --restart always elasticsearch:7.17.3`

> create container rabbitmq
> - `sudo docker run -d --name rabbitmq -p 5672:5672 -p 15672:15672 rabbitmq:3-management`

> create container mongodb
> - `docker run --name mongodb -d -p 27017:27017 --restart always mongo:latest`

```sudo rm -Rf /Applications/Docker.app
sudo rm -f /usr/local/bin/docker
sudo rm -f /usr/local/bin/docker-machine
sudo rm -f /usr/local/bin/com.docker.cli
sudo rm -f /usr/local/bin/docker-compose
sudo rm -f /usr/local/bin/docker-compose-v1
sudo rm -f /usr/local/bin/docker-credential-desktop
sudo rm -f /usr/local/bin/docker-credential-ecr-login
sudo rm -f /usr/local/bin/docker-credential-osxkeychain
sudo rm -f /usr/local/bin/hub-tool
sudo rm -f /usr/local/bin/hyperkit
sudo rm -f /usr/local/bin/kubectl.docker
sudo rm -f /usr/local/bin/vpnkit
sudo rm -Rf ~/.docker
sudo rm -Rf ~/Library/Containers/com.docker.docker
sudo rm -Rf ~/Library/Application\ Support/Docker\ Desktop
sudo rm -Rf ~/Library/Group\ Containers/group.com.docker
sudo rm -f ~/Library/HTTPStorages/com.docker.docker.binarycookies
sudo rm -f /Library/PrivilegedHelperTools/com.docker.vmnetd
sudo rm -f /Library/LaunchDaemons/com.docker.vmnetd.plist
sudo rm -Rf ~/Library/Logs/Docker\ Desktop
sudo rm -Rf /usr/local/lib/docker
sudo rm -f ~/Library/Preferences/com.docker.docker.plist
sudo rm -Rf ~/Library/Saved\ Application\ State/com.electron.docker-frontend.savedState
sudo rm -f ~/Library/Preferences/com.electron.docker-frontend.plist```
