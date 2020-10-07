# To build
# sudo docker build -t ctf:network-recon .
#
# To run
# sudo docker run -d --rm -v $PWD:/pwd -i ctf:network-recon
#
# Get [containerid]
# sudo docker ps
#
# To interact
# sudo docker exec -it [containerid] /bin/bash
#
# To stop
# sudo docker stop [containerid]
FROM ubuntu:19.10
ENV LC_CTYPE C.UTF-8
ENV DEBIAN_FRONTEND=noninteractive
RUN dpkg --add-architecture i386 && \
apt-get update && \
apt-get install -y nmap snmp
