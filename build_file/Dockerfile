FROM maven:3.6.3-jdk-8 as maven_builder
WORKDIR /test
RUN apt-get install -y git
RUN git clone https://github.com/koddas/war-web-project.git /test
RUN mvn  -f pom.xml package