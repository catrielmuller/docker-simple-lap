# Docker - Linux Apache PHP

## Build
```
docker build -t catrielmuller/simple-lap .
```
## Running

Modify the local_absolute for point to the project.

```
docker run -d -p 8080:80 -v /local_absolute/path:/app -e ALLOW_OVERRIDE=true catrielmuller/simple-lap
```
