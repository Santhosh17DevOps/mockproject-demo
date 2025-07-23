# Use official Tomcat 10 image 
FROM tomcat:10.1-jdk17

# Clean out default applications (docs, examples, ROOT)
RUN rm -rf /usr/local/tomcat/webapps/*

# Copy your WAR file into the webapps directory as ROOT.war
COPY maven-wrapper.war /usr/local/tomcat/webapps/ROOT.war

# Expose default Tomcat port
EXPOSE 8080
