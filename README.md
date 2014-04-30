#Boom container

Trusted build: [mirkokiefer/boom](https://index.docker.io/u/mirkokiefer/boom/).

Docker container for [boom](https://github.com/rakyll/boom), the http load generator.

**Build Dependencies**:
- [mirkokiefer/ubuntu-base](https://github.com/mirkokiefer/dockerfile-ubuntu-base)

You can run boom with:

```
docker run --rm mirkokiefer/boom -c 10 -n 100 http://yoururl.com
```
