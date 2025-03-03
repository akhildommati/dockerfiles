FROM almalinux:9
RUN dnf install nginx -y
# there is no functionality difference between the two LABELs
EXPOSE 80
CMD ["nginx", "-g", "daemon off;"]