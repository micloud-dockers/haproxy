# haproxy @ ubuntu

This is a small install haproxy on ubuntu.

## Run in daemon mode

```
docker run -d -it -v /home/simonsu/dockerws/haproxy:/haproxy \
  peihsinsu/haproxy \
  haproxy -d -f /haproxy/sample.cfg
```

## Run in iteractive mode

```
docker run -it -v /home/simonsu/dockerws/haproxy:/haproxy peihsinsu/haproxy bash
```

