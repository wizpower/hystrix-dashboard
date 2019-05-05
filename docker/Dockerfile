FROM openjdk:8
ADD hystrix-dashboard-0.0.1-SNAPSHOT.jar hystrix-dashboard.jar
RUN bash -c 'touch /hystrix-dashboard.jar'
ENTRYPOINT ["java","-jar","/hystrix-dashboard.jar"]
