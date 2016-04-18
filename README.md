Docker image for Gradle based on Alpine Linux
================


## Sample run command

```
docker run --rm -it -v $(pwd):/app -v $HOME/.gradle:/gradle andreirs/alpine-gradle clean build
```

## Mount Points

* `/app`: Working directory, where your build.gradle located
* `/gradle`: Gradle home directory, where the gradle cache located