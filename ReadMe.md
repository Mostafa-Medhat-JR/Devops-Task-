
**Name:** Mostafa Medhat Ahmed

## Part 1

docker run -d --name alpine_sleeper alpine sleep 1000
docker ps
docker stop alpine_sleeper
docker rm alpine_sleeper
docker ps
docker images
docker rmi 28bd5fe8b56d
docker images
```

---

## Part 2

docker run -it --name ubuntu-server ubuntu sh -c 'while true; do echo "Input website:"; read website; echo "Searching.."; sleep 1; curl http://$website; done'

docker exec -it ubuntu-server bash

apt update
apt install curl

exit
```

Input website:
helsinki.fi

Searching..

<html>
<head><title>301 Moved Permanently</title></head>
<body>
<center><h1>301 Moved Permanently</h1></center>
<hr><center>nginx/1.24.0</center>
</body>
</html>

Input website:
```
