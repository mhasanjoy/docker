## Pull an Image from Docker Hub

```
docker pull <image-name>:<image-tag>
```

## List Available Images

```
docker images
```

## Run a Container

```
docker run -p <machine-port>:<docker-port> --name <container-name> --rm <image-name>:<image-tag>
```

> **Interactive Mode**

```
docker run -it <image-name>
```

> **Detached Mode**

```
docker run -d <image-name>
```

## Stop a Running Container

```
docker container stop <container-name>
```

## Start a Stopped Container

```
docker container start <container-name>
```

> **Attached Mode**

```
docker container start -a <image-name>
```

## Remove a Stopped Container

```
docker container rm <container-name>
```

> **Remove All Stopped Containers**

```
docker container prune
```

## Remove an Image

```
docker image rm <image-name>
```

> **Remove Unused Images**

```
docker image prune
```
