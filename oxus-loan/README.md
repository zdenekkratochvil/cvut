# Oxus CRM referential component

## Build from source
mvn clean install docker:build

## Pull existing image
docker pull inxius/cvut-oxus-loan

## Run on local
docker run -p 8080:8080 -t inxius/cvut-oxus-loan

## Swagger UI
http://localhost:8080/
