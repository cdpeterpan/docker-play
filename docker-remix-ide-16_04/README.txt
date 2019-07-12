编译镜像
docker build -t remix:latest .

运行
docker run -p 8080:8080 --name remix remix

直接通过 http://localhost:8080 即可访问本地的Remix-IDE。
进入容器
docker exec -it remix /bin/bash

