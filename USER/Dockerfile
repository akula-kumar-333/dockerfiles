# bare minimum os
FROM almalinux
# installing nginx
RUN yum -y install nginx
# adding user
RUN adduser kumar
# giving read, write and executable permissions
RUN chmod 777 /usr/share/nginx/html/
# creating user
USER kumar
# creating file
RUN touch /usr/share/nginx/html/kumar.html
