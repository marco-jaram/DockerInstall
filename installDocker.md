## Docker in Archlinux
### Install
```
sudo pacmane -S docker docker-compose
```

Verifi
```
sudo systemctl status docker
```
Active

```
sudo systemctl enable docker
```

Version
```
docker version
```

Run
```
sudo docker run hello-world
```

### Whit permissions

 - verifi group
```
cat /etc/group
```
ADD acount

```
sudo usermod -aG docker marco 
```

```
newgrp docker

```




