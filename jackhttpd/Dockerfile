From busybox:1.31.0
LABEL maintain="Jack<csuxh@foxmail.com>" app="httpd"
ENV WEB_ROOT="/data/www/"
RUN mkdir -p $WEB_ROOT && \
  echo '<h1>Jacks Httpd Server v1.1</h1>' >> $WEB_ROOT/index.html
CMD /bin/httpd -f -h $WEB_ROOT
