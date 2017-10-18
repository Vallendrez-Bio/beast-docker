# beast-docker

Containerize [Beast](https://github.com/beast-dev/beast-mcmc)

## Running Beast

```
docker run -v /tmp/.X11-unix:/tmp/.X11-unix -e DISPLAY=unix$DISPLAY -v ~/.Xauthority:/home/developer/.Xauthority --rm -it --name beast testing beast
```
