# dockerimage_docker-proxy

Custom image of https://github.com/jwilder/nginx-proxy.
Run with `docker run -d -p 80:80 -v /var/run/docker.sock:/tmp/docker.sock:ro --name node-proxy  qurami/nginx-proxy`