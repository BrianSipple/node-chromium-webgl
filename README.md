# Node Chromium WebGL Dockerfile

[![dockeri.co][docker-badge-image]][docker-badge-url]


_A Docker image that extends the [`node:boron` image](https://github.com/nodejs/docker-node#nodeversion)
and provides a binary for running a headless, WebGL-enabled Chromium browser
inside of a Docker container_.

### Installation

- Install [Docker](https://www.docker.com/).

- Download the [automated build](https://registry.hub.docker.com/u/bsipple/node-chromium-webgl/) from the
public [Docker Hub Registry](https://registry.hub.docker.com/):

  ```sh
  docker pull bsipple/node-chromium-webgl
  ```

  + Alternatively, you can build an image from the Dockerfile:

      ```sh
      docker build -t="bsipple/node-chromium-webgl" github.com/BrianSipple/node-chromium-webgl
      ```

### Usage

```sh
docker run -it --rm bsipple/node-chromium-webgl /bin/bash
```


[docker-badge-image]: http://dockeri.co/image/bsipple/node-chromium-webgl/
[docker-badge-url]: https://hub.docker.com/r/bsipple/node-chromium-webgl/
