# docker-nginx-openssl1.0.2
Docker image for nginx 1.11.1 with openssl 1.0.2f and http2 module support

## What's inside
 - Nginx 1.9.6 build from source and installed
 - Openssl 1.0.2 build from source and installed
 - Nginx http_v2_module
 - Nginx http_stub_status_module
 - Nginx http_realip_module

##Purpose
This image is built primarily for having Nginx compiled with the Openssl 1.0.2 source. This is required to have ALPN
support with http2. The offical Nginx docker images, tag nginx:latest, doesn't have Openssl 1.0.2 source in the build.
