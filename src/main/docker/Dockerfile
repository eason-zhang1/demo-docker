FROM java:8
VOLUME /tmp
ADD  demo-boot_test.jar app.jar
#EXPOSE 8080
ENTRYPOINT ["java","-Djava.security.egd=file:/dev/./urandom"]
# CMD
CMD ["-jar", "app.jar"]