# replicas


dentro del compose existira 20 replicas de tomcat y servicios distintos para hacer reverse proxy:

- nginx 81
- haproxy 82
- traefik 83
- envoy 84

De todos el que mejor funciona esta entre traefik y envoy, y para algo mas clasico, el que mejor destaca es haproxy. Ya para cosas sencillas nginx.

Si no quieres levantar todos solo comentalos.

por defecto se crearan 20 replicas de tomcat.
