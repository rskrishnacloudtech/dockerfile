ARG version
FROM almalinux:${version:-8}
ARG user
ARG email
RUN echo "Name is: ${user}, email is ${email}"
ENV user=${user}
CMD [ "sleep","100" ]