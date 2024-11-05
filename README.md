# About

IP Address/UNIX Socket convenience functions for Go

https://github.com/hashicorp/go-sockaddr

## Usage

```Dockerfile
FROM swarmlibs/go-sockaddr:main AS go-sockaddr

FROM your-base-image
COPY --from=go-sockaddr /sockaddr /usr/bin/sockaddr
```
