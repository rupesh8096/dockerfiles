ARG VERSION
FROM almalinux:${VERSION :-9}
ARG COURSE= "Docker for Beginners"
RUN echo "Welcome to ${COURSE}"
ENV COURSE=${COURSE}
RUN echo "The value of COURSE is ${COURSE}" 
CMD ["sleep", "1000"]