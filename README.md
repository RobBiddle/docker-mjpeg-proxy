# docker-mjpeg-proxy

environment variable MJPEG_URL set:

```
docker run -it -p 8080:8080 -e MJPEG_URL='http://192.168.66.49:2971/camera/stream'  roflmao/docker-mjpeg-proxy
```

Access MJPEG stream at http://$host:$port/index.jpg
