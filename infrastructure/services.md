# Serveis

## virtual routing

es decideix que no VRRP, s'utilitza HA del cluster proxmox

## reverse proxy

reverse proxy: haproxy

gestió de certificats: certbot (letsencrypt)

Port | Servei | Descripció
---- | ------ | ----------
80/tcp | HTTP | força sempre redirecció a 443
443/tcp | HTTPS | SSL reverse proxy

reverse proxy i gestió de certificats:
- academia.exo.cat
- exo.cat
- public.exo.cat
- db.exo.cat
- noc.exo.cat
- privat.exo.cat
- data.exo.cat
- shop.exo.cat

només gestió de certificats (a revisar)
- meet.guifi.net
- xat.guifi.net
- matrix.exo.cat

## academia.exo.cat

software: drupal

## exo.cat

software: wordpress

- reduïr número de plugins; que sigui fàcil tenir-lo a la última versió
- agafar el calendari de data.exo.cat i incrustar-lo

## public.exo.cat

software: gogs.io

tot lo que hi ha al github ara (public, doc), github es convertiria llavors en un mirror d'aquest repositori

## db.exo.cat

software: django admin

informació integrada

https://github.com/guifi-org/exoadmin

## noc.exo.cat

software: cacti

- en un futur es pot plantejar tenir també weathermap, smokeping

## privat.exo.cat

software: gogs.io

repositoris que contenen informació personal

## data.exo.cat

software: nextcloud

- calendari eXO
- gestió de documents personals

## shop.exo.cat

software: prestashop

## meet.guifi.net

software: jitsi-meet

## xat.guifi.net

software: rocketchat

## matrix.exo.cat

software: matrix + riot

requeriments:
- com es faria integració ldap amb guifi
- si hi ha alguna característica important que perdem de rocketchat, especialment de comoditat pels usuaris més relaxats
- sé que es poden enllaçar rocketchat i matrix; el tema es fer-ho possible de veritat. així doncs, la migració no seria tant greu. hi hauria un període que funcionarien tots dos