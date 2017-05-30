# docker-logrotate
Logrotation into docker containers


## Getting source
```
git clone https://github.com/danielef/docker-logrotate
```

## Building
```
docker build --rm -t danielef/logrotate .
```

## Running
### Example
```
docker run -v /Users/username/logs:/opt/logs -v /Users/username/docker-logrotate/logrotate.conf:/etc/logrotate.conf danielef/logrotate
```
