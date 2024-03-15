# bge-m3-server

``` bash
docker build --build-arg=USE_CHINA_MIRROR=true --progress plain .
docker run -it --rm -p3001:3000 luoweb/bge-m3-server:latest
docker run -it --rm -p3001:3000 -v/Users/block/code/llm/bge-m3:/bge-m3 luoweb/bge-m3-server:latest

```
