# tick-docker-stack

Updated TICK stack https://github.com/influxdata/TICK-docker for Docker Stack.
Customize conf/traefik.tml with custom login, email and password:

openssl passwd -apr1 -salt SALT PASSWD

Create a /data directory and put "conf" in (or modify according to your taste)
