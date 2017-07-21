FROM nginx

COPY nginx.conf /etc/nginx/nginx.conf

# 用于配置ssl
RUN mkdir -p /data/ssl && chown -R nginx:nginx /data/ssl
VOLUME /data/ssl
