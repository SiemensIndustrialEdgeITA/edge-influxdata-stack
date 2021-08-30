#from base image
FROM telegraf:1.10.4-alpine

#copy configuration file
COPY ./telegraf.conf /etc/telegraf/telegraf.conf

# Set up default values for enviromental variables
ENV HOST_PROC="/rootfs/proc"
ENV HOST_SYS="/rootfs/sys"
ENV HOST_ETC="/rootfs/etc"
ENV HOST_VAR="/host/var"
ENV AGENT_INTERVAL="10s"
ENV AGENT_FLUSHINTERVAL="10s"


