FROM fabric8/java-alpine-openjdk8-jdk
RUN adduser -D balanzUser
ARG JAR_FILE
COPY ${JAR_FILE} ./home
EXPOSE 8080
RUN chown -R balanzUser:balanzUser /home
USER balanzUser
CMD ["java","-jar","/home/passwordapi.jar"]