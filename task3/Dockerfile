FROM ubuntu
RUN apt-get update
RUN apt-get install -y firefox
RUN groupadd -g 1000 mukesh

RUN useradd -d /home/mukesh -s /bin/bash -m rhythm -u 1000 -g 1000
USER mukesh
ENV HOME /home/mukesh
CMD /usr/bin/firefox
