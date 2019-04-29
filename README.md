# Dockerfiles
A collection of dockerfiles for building images for utility purposes.

## Building images
```shell
docker build -f /path/to/<dockerfile> -t <docker-image-tag> .
```

## Running images


## Dockerfile directory


### Kali linux
Image with metasploit. Used CTFs.
Will be updated with additonal tooling over time.

#### Building and running image

```shell
docker build -f ./Dockerfile.kali-linux -t kali .
docker run -it kali
```

