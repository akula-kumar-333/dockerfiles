FROM almalinux
RUN yum -y install nginx
RUN rm -f /usr/share/nginx/index.html
COPY qi /usr/share/nginx/html/
EXPOSE 80/tcp
ENTRYPOINT ["nginx", "-g"]
CMD ["daemon off;"]
