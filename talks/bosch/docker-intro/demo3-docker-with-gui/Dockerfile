FROM ubuntu:20.04

RUN apt-get update && \
    apt-get install -y --no-install-recommends \
        libcanberra-gtk-module \
        libcanberra-gtk3-module \
        firefox \
        gedit && \
    apt clean

CMD ["gedit"]