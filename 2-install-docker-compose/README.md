

# install
```
sudo curl -L "https://github.com/docker/compose/releases/download/1.27.4/docker-compose-$(uname -s)-$(uname -m)" -o /usr/local/bin/docker-compose
sudo chmod +x /usr/local/bin/docker-compose
sudo ln -s /usr/local/bin/docker-compose /usr/bin/docker-compose
```

## verify 
```
docker-compose --version
```

# uninstall
```
sudo rm /usr/local/bin/docker-compose
```


# references
-[install](https://docs.docker.com/compose/install/)