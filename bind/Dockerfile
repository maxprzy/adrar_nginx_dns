FROM sameersbn/bind:latest

ENV ROOT_PASSWORD=Azerty77

COPY ./conf/named.conf.local /data/bind/etc/named.conf.local
COPY ./conf/cours.lan.hosts /data/bind/lib/cours.lan.hosts

EXPOSE 53/TCP 53/UDP 10000
