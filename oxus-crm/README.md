# Oxus CRM referential component

## Build from source
mvn clean install docker:build

## Pull existing image
docker pull inxius/cvut-oxus-crm

## Run on local
docker run -p 8080:8080 -t inxius/cvut-oxus-crm

## Swagger UI
http://localhost:8080/

## Mock Data
client id 1-5