# busybox-base
![Docker Pulls](https://img.shields.io/docker/pulls/forumi0721/busybox-base)
![Docker Stars](https://img.shields.io/docker/stars/forumi0721/busybox-base)



----------------------------------------
### x64
![Docker Image Version](https://img.shields.io/docker/v/forumi0721/busybox-base/latest)
![Docker Image Size](https://img.shields.io/docker/image-size/forumi0721/busybox-base/latest)
### aarch64
![Docker Image Version](https://img.shields.io/docker/v/forumi0721/busybox-base/aarch64)
![Docker Image Size](https://img.shields.io/docker/image-size/forumi0721/busybox-base/aarch64)



----------------------------------------
#### Description

* Distribution : [Busybox](https://busybox.net/)
* Architecture : x64,aarch64
* Appplication : -



----------------------------------------
#### Run

```sh
docker run -i -t --rm \
           forumi0721/busybox-base:[ARCH_TAG]
```



----------------------------------------
#### Usage

```dockerfile
FROM forumi0721/busybox-base:[ARCH_TAG]

#For cross compile on dockerhub (aarch64)
RUN ["docker-build-start"]

RUN 'build-code'

#For cross compile on dockerhub  (aarch64)
RUN ["docker-build-end"]
```



----------------------------------------
#### Docker Options

| Option             | Description                                      |
|--------------------|--------------------------------------------------|
| -                  | -                                                |


#### Ports

| Port               | Description                                      |
|--------------------|--------------------------------------------------|
| -                  | -                                                |


#### Volumes

| Volume             | Description                                      |
|--------------------|--------------------------------------------------|
| -                  | -                                                |


#### Environment Variables

| ENV                | Description                                      |
|--------------------|--------------------------------------------------|
| -                  | -                                                |

