FROM braucher/php
MAINTAINER Jeff Braucher <jeff@braucher.net>

# Configure the system with puppet
COPY ./puppet/ /puppet-app/
ENV PUPPET_HOME /puppet-app
RUN /puppet-apply

# Run php
EXPOSE 9000
COPY ./app* /
ENTRYPOINT ["/app"]
CMD ["start"]

