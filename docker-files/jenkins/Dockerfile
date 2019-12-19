FROM jenkins/jenkins
USER root
RUN apt-get update && apt-get install -y make git maven openjdk-8-jdk
USER jenkins
ENV JAVA_HOME /usr/lib/jvm/java-8-openjdk-amd64
ENV MAVEN_HOME /usr/share/maven