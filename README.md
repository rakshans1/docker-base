[![Travis](https://img.shields.io/travis/rakshans1/docker-base.svg)](https://travis-ci.org/rakshans1/docker-base)
[![Pulls](https://img.shields.io/docker/pulls/rakshans1/base.svg)]()
[![Layers](https://img.shields.io/imagelayers/layers/rakshans1/base/latest.svg)]()
[![Size](https://img.shields.io/imagelayers/image-size/rakshans1/base/latest.svg)]()

![rakshans1/base](/icon.svg?raw=true)
# Linux base image (`FROM Ubuntu 16.04`)
----
### Pull from Docker Hub
```
docker pull rakshans1/base:latest
```

### Build from GitHub
```
docker build -t rakshans1/base github.com/rakshans1/docker-base
```

### Run image
```
docker run -it rakshans1/base bash
```

### Use as base image
```Dockerfile
FROM rakshans1/base:latest
```