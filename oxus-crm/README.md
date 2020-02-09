# Oxus CRM referential component

###Build
mvn clean install docker:build

###Pull
docker pull inxius/cvut-oxus-crm

###Run
docker run -p 8080:8080 -t inxius/cvut-oxus-crm

###Swagger UI
http://localhost:8080/

###Mock Data
client id 1-5