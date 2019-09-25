# Pull base image
FROM 9-jdk8-corretto

# Maintainer
MAINTAINER "ravindu@emojot.com"
# Set Environment properties
ENV JAVA_OPTS=-Denvironment=production

# Copy war file to tomcat webapps folder
COPY /dockermavensample.war /usr/local/tomcat/webapps/
