FROM nginxinc/nginx-unprivileged:alpine
WORKDIR apps/nginx-hello-world
COPY ./nginx.conf /etc/nginx/nginx.conf

USER 1000
EXPOSE 8080