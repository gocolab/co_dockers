#### Only CLI
```
~$ docker pull python:3.11
~$ docker run -it --name python_3_11 python:3.11 /bin/bash
~$ docker exec -it python_3_11 /bin/bash   # reRun
```
#### CLI with Dockerfile and compose.xml
```
~$ docker-compose build
~$ docker-compose up -d
~$ docker exec -it <컨테이너 id> /bin/bash     # reRun
```
