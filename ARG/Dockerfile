ARG version
FROM almalinux:${version:-8}
# here, version:-8 means, if user is not given any version while image build in command line, then it will take the default version as 8.
ARG COURSE=Docker
ARG TRAINER=Mahi
ARG DURATION=120Days
ENV DURATION={DURATION}
RUN echo "Course is: ${COURSE}, Trainer is: ${TRAINER}, Duration is: ${DURATION}"
CMD [ "sleep", "100" ]