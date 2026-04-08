FROM almalinux:9
RUN dnf install nginx -y 
EXPOSE 80 
CMD ["nginx", "-g", "daemon off;"]






#Expose dnt really open port, it just shows which port is used

#RUN is used at the time of building the image

#CMD is used at the time of running the container
#only one CMD is present in a dockerfile, if multiple CMD is present only the last one will be considered
