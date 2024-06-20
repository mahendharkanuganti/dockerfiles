FROM almalinux:9
RUN useradd expense
USER expense
CMD [ "sleep", "100" ]

#if we did not specify the user in any docker image, it will directly go into root user in the container.
