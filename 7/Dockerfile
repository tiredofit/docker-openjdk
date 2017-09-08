FROM tiredofit/alpine:3.6
LABEL maintainer="Dave Conroy (dave at tiredofit dot ca)"

   ENV JAVA_HOME="/usr/lib/jvm/default-jvm"

   RUN apk update && \ 
       apk add \
           openjdk7 && \
       rm -rf /tmp/* /var/cache/apk/*


