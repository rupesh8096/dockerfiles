FROM almalinux:9
RUN dnf -y install nginx && dnf clean all
RUN useradd -m -s /bin/bash cgrupesh
USER cgrupesh
CMD ["nginx", "-g", "daemon off;"]