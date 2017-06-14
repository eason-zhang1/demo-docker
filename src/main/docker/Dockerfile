FROM java:8
VOLUME /tmp
ADD  demo-boot_test.jar api.jar
EXPOSE 8080
ENTRYPOINT ["java","-jar","-Duser.timezone=Asia/Shanghai","-Dfile.encoding=utf-8","-Duser.language=zh","/api.jar"]
CMD ["sh"]