docker stack deploy --compose-file=/home/administrator/BenNetDock-Stack/Guac-Stack.yml BenNetDock-Guacamole
docker stack deploy --compose-file=/home/administrator/BenNetDock-Stack/Plex-Stack.yml BenNetDock-Plex
docker stack deploy --compose-file=/home/administrator/BenNetDock-Stack/Unifi-Stack.yml BenNetDock-Unifi
docker stack deploy --compose-file=/home/administrator/BenNetDock-Stack/Portainer-Stack.yml BenNetDock-Portainer
docker stack deploy --compose-file=/home/administrator/BenNetDock-Stack/Tor-Stack.yml BenNetDock-Torrent

