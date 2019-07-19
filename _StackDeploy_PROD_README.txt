docker stack deploy --compose-file=/home/administrator/BenNetDock-Stack/Guac-Stack-PROD.yml BenNetDock-Guacamole
docker stack deploy --compose-file=/home/administrator/BenNetDock-Stack/Plex-Stack-PROD.yml BenNetDock-Plex
docker stack deploy --compose-file=/home/administrator/BenNetDock-Stack/Unifi-Stack-PROD.yml BenNetDock-Unifi
docker stack deploy --compose-file=/home/administrator/BenNetDock-Stack/Portainer-Stack-PROD.yml BenNetDock-Portainer
docker stack deploy --compose-file=/home/administrator/BenNetDock-Stack/Tor-Stack-PROD.yml BenNetDock-Torrent

