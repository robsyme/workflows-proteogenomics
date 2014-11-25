FROM ubuntu:14.04

MAINTAINER Robert Syme <rob.syme@gmail.com>


RUN mkdir /opt/crux
ADD lib/crux-2.1.Linux.x86_64.tar.gz /opt/crux/
RUN ln -s /opt/crux/crux-* /opt/crux/current

ENV PATH /usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin:/opt/crux/current/bin

CMD /opt/crux/current/bin/crux
