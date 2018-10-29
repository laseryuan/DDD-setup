# Usage
```
docker run --name=crmux --rm -it --net=host --pid=host lasery/crmux:18.10
```
ctrl-c multiple times to exit

# Development
```
cd ~/projects/DDD-setup/tools/crmux
docker build -t lasery/crmux .
docker run --name=crmux --rm -it --net=host --pid=host lasery/crmux

docker tag lasery/crmux lasery/crmux:18.10
docker push lasery/crmux:18.10
```
