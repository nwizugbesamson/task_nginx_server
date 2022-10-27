## download offical alpine nginx image
FROM nginx:1.23-alpine


## remove default config file and replace with custom
RUN rm /etc/nginx/conf.d/default.conf
COPY nginx.conf /etc/nginx/conf.d