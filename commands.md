# namespaceandcgroup

## Commands

grep -E '^CONFIG_USER_NS=' /boot/config-$(uname -r)


sudo systemctl restart docker


docker run -it nginx sleep 300


docker ps


ps -aux | grep sleep


cat /etc/subuid


sudo docker info


sudo docker run -it -rm -v /bin:/host/bin busybox /bin/sh 


 id


rm host/bin/sh


docker images


docker run --cpus 0.5 d453dd892d93


docker ps


docker stats d0855830c374


docker run -d --name new-container --memory=256M ubuntu sleep infinity


docker ps


docker stats d67613c74bd6


docker stats new-container --no-stream --format "{{ json . }}" | python3 -m json.tool
