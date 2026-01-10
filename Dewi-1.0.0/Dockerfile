FROM nginx:alpine

# hapus config default
RUN rm -rf /usr/share/nginx/html/*

# copy static web
COPY . /usr/share/nginx/html

EXPOSE 80

