FROM scratch
MAINTAINER Munjal Patel <munjalpatel@gmail.com>

ADD rootfs.tar /
ADD .foreverignore /home/default/

USER default

ENV HOME /home/default
ENV NODE_PATH /usr/lib/node_modules
ENV PATH /usr/lib/node_modules/forever/bin:/usr/lib/node_modules/npm/bin:$PATH

WORKDIR /home/default
ENTRYPOINT ["forever"]

