# MTA:SA Docker Image

This is a dockerfile config to set up a MTA:SA Server on docker.

## Links
- https://hub.docker.com/r/ciber96/mtasa-docker

## Installation for Use Out of the Box
```bash
docker pull ciber96/mtasa-docker
docker run -it \
-p 22003:22003/udp \
-p 22005:22005 \
-p 22126:22126/udp \
--name mta-server \
-d ciber96/mtasa-docker
```
## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## Known Issues
None
