FROM jboss/base-jdk:8

ADD /target/SparkJava-sample.jar /opt/SparkJava-sample.jar
ADD /target/dependency-jars/ /opt/dependency-jars/

ENTRYPOINT ["java", "-jar", "/opt/SparkJava-sample.jar", "-Djava.net.preferIPv4Stack=true"]
