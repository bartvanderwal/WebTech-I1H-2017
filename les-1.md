https://github.com/somatorio/docker-packet-tracer

docker run -it --rm \
  -e DISPLAY=unix$DISPLAY \
  -v /tmp/.X11-unix/:/tmp/.X11-unix/ \
  -v $HOME/.packettracer:/root/pt \
  somatorio/packet-tracer