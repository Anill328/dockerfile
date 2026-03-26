FROM almalinux:9
RUN dnf install nginx -y 
# root acces required to create user or to install packages
RUN useradd roboshop
USER roboshop
CMD ["sleep","100"]