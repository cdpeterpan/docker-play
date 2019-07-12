build image:
docker build -t remix:latest .

run:
docker run -p 8080:8080 --name remix remix

access local remix-id via browser, url:http://localhost:8080

entry container:
docker exec -it remix /bin/bash

###Ref:
**remix-ide-docker without remixed**
*can not connect to local file folder*
![remix-ide-docker](https://www.jianshu.com/p/a4ab7aac87c3 "remix-ide-docker")

###TODO:
1. reduce image layer
2. optomizing download speed necessary
