ARG NGINX_VERSION
FROM nginx:${NGINX_VERSION}

COPY docker-entrypoint /usr/local/bin/
RUN chmod +x /usr/local/bin/docker-entrypoint

ENTRYPOINT ["docker-entrypoint"]

CMD ["nginx", "-g", "daemon off;"]
