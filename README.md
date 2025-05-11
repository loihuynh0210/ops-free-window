# ops-free-window
https://github.com/dockur/windows

# install os
sudo apt update
sudo apt install docker.io docker-compose -y

# docker run window
sudo docker-compose -f win10.yml up -d

# docker run macos
sudo docker-compose -f macos.yml up -d

# docker logs
docker logs windows

#remove images and re run
docker system prune -a

