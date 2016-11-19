# docker-open-zwave-control-panel
##Build
```sh
docker build -t tobre/rpi-open-zwave-control-panel .
```

##Run
```sh
docker run -d -p 8090:8090 --name="ozwcp" --device=/dev/ttyACM0 tobre/rpi-open-zwave-control-panel
```
