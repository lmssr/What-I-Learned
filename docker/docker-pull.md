# Docker Pull 

The pull command is used when you want to pull the docker image from dockerhub (docker repository). The following example of pulling the Apache HTTP server image.


```sh
docker pull <image name>
```

- Here’s an example of docker pull command
```sh
❯ docker pull httpd
Using default tag: latest
latest: Pulling from library/httpd
bd159e379b3b: Already exists
36d838c2f6d6: Pull complete
b55eda22bb18: Pull complete
f6e6bfa28393: Pull complete
a1b49b7ecb8a: Pull complete
Digest: sha256:4400fb49c9d7d218d3c8109ef721e0ec1f3897028a3004b098af587d565f4ae5
Status: Downloaded newer image for httpd:latest
docker.io/library/httpd:latest
```

