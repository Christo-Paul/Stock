# Stock
edit logstash.conf  source kafka, dest localhost 9092-elastic  -start logstash
start elastic
start kibana afterediting kibana.yml , then craete index


spring:
  application:
    name: stock-app
    
eureka:
  client:
    register-with-eureka: true
    fetch-registry: true
    serviceUrl:
      defaultZone: http://localhost:8761/eureka

C:\Users\User>zookeeper-server-start.bat C:\Users\User\Downloads\kaf\config\zookeeper.properties
C:\Users\User>kafka-server-start.bat C:\Users\User\Downloads\kaf\config\server.properties
C:\Users\User>kafka-console-consumer.bat --bootstrap-server localhost:9092 --topic devglan-test


$ mvn sonar:sonar   -Dsonar.projectKey=CompanyApplicationService   -Dsonar.host.url=http://localhost:9000   -Dsonar.login=bd1055867e8fee523279f94624be2c2aed5df7fe

