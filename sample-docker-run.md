```
docker run \
  --name=my-container \
  --restart=always \
  --log-driver=gelf \
  --log-opt gelf-address=udp://ip:12201 \
  -d namespace/image
```
