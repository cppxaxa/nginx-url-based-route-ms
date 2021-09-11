# nginx-url-based-route-ms

* First download the nginx in either the linux, or windows
* In case of docker, be sure to set the CMD as
> CMD ["nginx", "-g", "daemon off;"]

# Modifications
* Find the sections - "server" and replicate the "location"
* In-case we're not able to fix hostnames, set the "upstream" under "http"

# Linux paths
* /etc/nginx/nginx.conf
* /etc/nginx/conf.d/default.conf
