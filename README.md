# Iniciar contêineres com docker compose

$ TAGELK=7.4.2 TAGGRAF=master-ubuntu docker-compose up -d
 
 
 Remove conteineres criados depois do Kibana
 
 docker rm -f $(docker ps -aq -f since=kibana)
