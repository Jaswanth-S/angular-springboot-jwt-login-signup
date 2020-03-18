FROM nginx:alpine
COPY default.conf /etc/nginx/conf.d/default.conf
## From 'builder' stage copy over the artifacts in dist folder to default nginx public folder
COPY /dist/GoldiesGym/ /usr/share/nginx/html