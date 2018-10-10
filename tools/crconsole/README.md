# Usage
```
docker run --name=crconsole --rm -it --net=host --pid=host lasery/crconsole:18.10
```
ctrl-c multiple times to exit

# Development
```
cd ~/projects/DDD-setup/tools/crconsole
docker build -t lasery/crconsole .
docker run --name=crconsole --rm -it --net=host --pid=host lasery/crconsole

docker tag lasery/crconsole lasery/crconsole:18.10
docker push lasery/crconsole:18.10
```
