# Docker Run 

The run command is used when you want to run an image (it doesn't matter if you pulled it before. If you have not the image loccaly, it will pull it for you). The following example of running the Apache HTTP server image.


```sh
docker run <image name>
```

- Here’s an example of docker pull command
```sh
❯ docker run httpd
AH00558: httpd: Could not reliably determine the server's fully qualified domain name, using 172.17.0.2. Set the 'ServerName' directive globally to suppress this message
AH00558: httpd: Could not reliably determine the server's fully qualified domain name, using 172.17.0.2. Set the 'ServerName' directive globally to suppress this message
[Thu Oct 13 15:00:45.549718 2022] [mpm_event:notice] [pid 1:tid 139791459097920] AH00489: Apache/2.4.54 (Unix) configured -- resuming normal operations
[Thu Oct 13 15:00:45.552571 2022] [core:notice] [pid 1:tid 139791459097920] AH00094: Command line: 'httpd -D FOREGROUND'```

