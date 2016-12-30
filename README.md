# Docker - Linux Apache PHP

## Build
```
docker build -t catrielmuller/simple-lap .
```
## Running
```
docker run -d -p 8080:80 -e ALLOW_OVERRIDE=true catrielmuller/simple-lap
```
