# open-api-generator

#### This guide assumes you have the following installed:
* [Apache Maven](https://maven.apache.org/install.html)
* [Node.js](https://nodejs.org/en/download/)
* [OpenAPI Generator](https://openapi-generator.tech/docs/installation/)
* [Postman](https://www.postman.com/downloads/)

Once that's sorted:
* Clone this repo into a local directory: ``git clone https://github.com/AshFernandes-IW/open-api-generator/``
* Open a terminal in the same directory and run ``npm install @openapitools/openapi-generator-cli -g``


You will notice our ``EnumConverterConfiguration.java`` file located in ``src/main/java/org/openapitools/configuration`` is not properly refactored.
* Capitalize ``partyinvolvementtypevalues`` and ``partytypevalues`` before importing the desired packages
* Once there are no more linting errors, run ``mvn clean spring-boot:run`` in your terminal
* Open up ``localhost:8080`` and you will be introduced to the Swagger index page
