# cloudbeaver web数据库工具

https://github.com/dbeaver/cloudbeaver/wiki/Run-Docker-Container

https://github.com/dbeaver/cloudbeaver

sudo docker pull dbeaver/cloudbeaver:latest

sudo docker run --name cloudbeaver --rm -ti -p 8080:8978 -v /var/cloudbeaver/workspace:/opt/cloudbeaver/workspace dbeaver/cloudbeaver:latest

# 一款SQL检查审核工具(MySql)

wget https://github.com/cookieY/Yearning/releases/download/v2.3.3/Yearning-2.3.3.2-linux-amd64.zip

[dbeaver 数据库工具：](https://dbeaver.io/download/)

## Dbeaver 
```bash
sudo  wget -O /usr/share/keyrings/dbeaver.gpg.key https://dbeaver.io/debs/dbeaver.gpg.key
echo "deb [signed-by=/usr/share/keyrings/dbeaver.gpg.key] https://dbeaver.io/debs/dbeaver-ce /" | sudo tee /etc/apt/sources.list.d/dbeaver.list
sudo apt-get update && sudo apt-get install dbeaver-ce
```
