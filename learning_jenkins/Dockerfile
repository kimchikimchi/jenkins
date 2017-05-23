FROM jenkins
USER root
RUN apt-get update && apt-get install -y maven
# Drop back to non-root user for security after pkg installation
USER jenkins
