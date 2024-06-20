ARG version
FROM almalinux:${version:-9}
ARG TOPIC=DOCKER
ARG TIME=WEEK
ARG CONDITION=MEDIUM
ENV CONDITION=${CONDITION}
RUN echo "topic is:${TOPIC}, time is:${TIME} and conditon is: ${CONDITION}"
CMD ["sleep","150"]
