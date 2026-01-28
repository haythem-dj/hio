FROM nginx:alpine

WORKDIR /app

COPY conf.d /etc/nginx/conf.d
COPY landing /usr/share/nginx/html

EXPOSE 80
CMD ["nginx", "-g", "daemon off;"]

