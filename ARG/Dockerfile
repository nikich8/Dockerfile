ARG version
FROm almalinux:${version}
ARG username
RUN adduser $username
USER $username
ARG COURSE
ARG TRAINER
RUN echo "course: ${COURSE}, Trainer: ${TRAINER}"
ENV COURSE=${COURSE}
ENV TRAINER=${TRAINER}
CMD ["sleep","100"]