### Ubuntu 18.04 + GCC (7.5.0) + CMake (3.10.2) + Git

#### Building to a Docker image
```sh
docker build -t iorfanidi/ubuntu-18.04-gcc-cmake-git:latest https://github.com/IvanOrfanidi/docker-images-ubuntu-18.04-gcc-cmake-git.git
```

#### Running the container
```sh
docker run -it --rm iorfanidi/ubuntu-18.04-gcc-cmake-git
```
