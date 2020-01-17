# Base Image.
FROM openjdk:8 

# Owner Name
MAINTAINER Nitin Jain <jain.nitin9@gmail.com> 


# Copy My Code. 
COPY spring-boot-sample-atmosphere-1.4.0.BUILD-SNAPSHOT.jar /

# EXPOSE the PORT 
EXPOSE 8080

# Start Apache Service
CMD ["java", "-jar", "spring-boot-sample-atmosphere-1.4.0.BUILD-SNAPSHOT.jar"]
