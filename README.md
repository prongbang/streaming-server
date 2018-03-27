# Streamming Server
> Using [nginx-rtmp](https://github.com/awakening-church/awakening-nginx-rtmp)
## Start
```
docker-compose up -d
```

## Stop
```
docker-compose down
```

## How to use
```
rtmp://{your-server}:1935/live/{your-stream-key}
```

> Example
```
rtmp://192.168.1.10:1935/live/live-streamming
```

> Watching the steam
```
http://{{your-server}:1935/hls/{your-stream-key}.m3u8
```
