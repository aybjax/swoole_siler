### running server
#### building
```
docker build -f ./Dockerfile -t swoole-php .
```
#### running server.php
```
docker run --rm -p 9501:9501 -v $(pwd):/app -w /app swoole-php server.php
```