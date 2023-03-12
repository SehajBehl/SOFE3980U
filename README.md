## SOFE3980U-Lab2

Apache Maven is an application which is used to intricately develop and preserve java-based and object oriented programs. Project deliverable two, is meant for students to build a web application and an API service based on a binary class which was implemented in deliverable one using Spring Boot to test both web and API applications. The deliverable included adding new dependencies such as Spring Boot framework, along with testing, creating documentation and implementing operators.

### Installation

To run the application, execute the following command:  

`$ mvn spring-boot:run`

### Tests

To run the test suite, execute the following command:  

`$ mvn test`

It is also possible to run the tests and the application right after:  

`$ mvn test spring-boot:run`

### Deploy on Google Cloud using Kubernetes

To deploy the application on GCP using Kubernetes, run the following commands:

```
$ git clone https://github.com/SehajBehl/SOFE3980U-Lab2
$ mvn package
$ kubectl create -f kubernetes/webapp-deploy.yml
$ kubectl create -f kubernetes/webapp-service.yml
```
