FROM nginx:latest

#COPY "index_replace.html" "/usr/share/nginx/html/index.html"
WORKDIR /usr/share/nginx/html
COPY "index_replace.html" "index.html"
RUN chmod 777 /usr/share/nginx/html