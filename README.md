dockui
======

WCO - ALLINCLOUD.FR - DOCKUI

Usage :
docker pull allincloud/dockui
docker run -d -p 9000:9000 -v /var/run/docker.sock:/docker.sock rudy/dockerui -e /docker.sock

If you're running as root, please use this line : (be carefull, it's not secure)
docker run -d -p 9000:9000 --privileged -v /var/run/docker.sock:/docker.sock rudy/dockerui -e /docker.sock
