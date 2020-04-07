# Spring Demo

* Spring Web
* Spring Boot Actuator
* Spring Data JPA
* Spring Data REST

## Build
`./mvnw clean package`

## Create Database
`cf create-service p.mysql db-small spring-demo-db`

## Sample [HTTPie](https://httpie.org/) requests to exercise REST API
`http post "spring-demo-wise-mouse-ew.cfapps.io/person/1" firstName=Fred lastName=Flintstone`

`http post spring-demo-wise-mouse-ew.cfapps.io/person firstName=Fred lastName=Flintstone`
