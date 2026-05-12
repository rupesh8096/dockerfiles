FROM almalinux:9
RUN dnf -y install nginx && dnf clean all
CMD ["nginx", "-g", "daemon off;"]