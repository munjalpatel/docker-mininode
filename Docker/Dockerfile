FROM scratch
MAINTAINER Munjal Patel <munjalpatel@gmail.com>
ADD rootfs.tar /

USER default

ENV HOME /home/default
ENV NODE_PATH /usr/lib/node_modules
ENV PATH /usr/lib/node_modules/forever/bin:/usr/lib/node_modules/npm/bin:$PATH

RUN touch /home/default/.foreverignore

WORKDIR /home/default
ENTRYPOINT ["forever"]

