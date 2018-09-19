Running the container in Docker:

```
docker run -d --network host --name sonos-controller carlosedp/sonos-web-controller
```

This will expose the interface on port 8080 as default. The container needs to be run on host network to find Sonos speakers.
