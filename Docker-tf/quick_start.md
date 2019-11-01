```
docker build Docker-srs --build-arg user=root --build-arg password=makefog -t aia3:std-ssh
docker run -it --rm -p 6422:22 -p 5001:5000 -p 6406:6006 -p 8778:8888 -d aia3:std-ssh
```





