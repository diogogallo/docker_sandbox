FROM java:7
COPY ../java/HelloDocker.java /
RUN javac HelloDocker.java
EXPOSE 8080
ENTRYPOINT ["java"]
CMD ["HelloDocker"]