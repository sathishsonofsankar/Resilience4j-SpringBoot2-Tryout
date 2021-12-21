# Resilience4j-SpringBoot2-Tryout
Just a base sample tryout for resilience4j library

Resilience Modules used is ratelimiter with fallback option.

To build :
mvn clean install

To run & execute :
java -jar target/<jar-name>
 
  
To do:
  Implement repository Layer using MongoDB
  Use retry with ratelimiter failure exception
  
Use Prometheus & grafanna to get a dashboard of available threads and permissions available.
