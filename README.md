#### **docker-compose**部署**nextcloud**服务

> 数据库使用了`mariadb`，缓存使用了`redis`

1. 克隆项目至本地;

   ```shell
   git clone https://github.com/Waterman1997/docker-compose-nextcloud.git && cd docker-compose-nextcloud
   ```

2. 使用docker-compose部署服务;

   ```shell
   docker-compose up -d
   ```

3. 浏览器打开http://ip:8080尽情使用.