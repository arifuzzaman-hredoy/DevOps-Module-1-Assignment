FROM nginx:alpine

LABEL maintainer="DevOps Lab"
LABEL description="Local DevOps demonstration application"

COPY app/ /usr/share/nginx/html/

EXPOSE 80

CMD ["nginx", "-g", "daemon off;"]
