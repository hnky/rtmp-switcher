# Docs


### Create a mixer

Url: localhost:3030/mixers

```
{
    "name":"henktv",
    "framerate": 30,
    "width":1920,
    "height":1080
}
```

### Create an output

Url: localhost:3030/mixers/henktv/outputs
```
{
    "name":"ams",
    "output_type": "RTMP",
    "location": "rtmp://evntz-hbo-tst-91ce-evntz-euwe.channel.media.azure.net:1935/live/43f4326778dd4f0fae678187b9fc9419",
    "encoder": {
        "video": {
            "encoder":"NVENC"
        }
    }
}
```

### Create an input
```
{
    "name":"henkshome",
    "input_type":"URI",
    "location": "rtmp://xxx"
}
```
