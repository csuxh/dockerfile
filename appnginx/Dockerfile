From nginx:alpine
LABEL maintain="Jack<csuxh@foxmail.com>" app="httpd"
#RUN ifconfig eth0 | grep inet | sed s/^.*addr://g  | sed s/Bcast.*$//g > /etc/ipaddr && \
RUN echo 'Hello MyApp | Version: v1.2 | <a href="hostname.html">Pod Name</a>' > /usr/share/nginx/html/index.html
ADD default.conf /etc/nginx/conf.d/default.conf
EXPOSE 80
ENTRYPOINT nginx -g "daemon off;"
#CMD ifconfig eth0 | grep inet | sed s/^.*addr://g  | sed s/Bcast.*$//g > /etc/ipaddr
