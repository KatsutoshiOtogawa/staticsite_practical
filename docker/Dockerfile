ARG NGINX_VERSION=1.19.2
FROM nginx:${NGINX_VERSION}

LABEL mainter="katsutoshi"

# 変更前のファイルをおいておく。
RUN cp /etc/nginx/nginx.conf /etc/nginx/nginx.conf.org
RUN cp /etc/nginx/conf.d/default.conf /etc/nginx/conf.d/default.conf.org

COPY docker/nginx.conf /etc/nginx/nginx.conf
COPY docker/default.conf /etc/nginx/conf.d/default.conf
