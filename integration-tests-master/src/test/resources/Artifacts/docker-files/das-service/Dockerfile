FROM dockerhub.private.wso2.com/maneesha-ubuntu-16.04_oracle-java-8.121:1.0

COPY init.sh /usr/local/bin/init.sh
RUN chmod +x /usr/local/bin/init.sh

# Docker Entry Point
ENTRYPOINT ["/usr/local/bin/init.sh"]