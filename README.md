# medicare-restapi-poc (SpringBoot+Gradle+MongoDB)
rest api with exception handling

#Instructions to run the project

Run query using POSTMAN Chrome App

URLs/endpoints to hit:

To get records of all doctors -->> GET http://localhost:8080/medicare/api/doctors

To get records of a doctor by id -->> GET http://localhost:8080/medicare/api/doctors/2

To insert record of a doctor -->> POST http://localhost:8080/medicare/api/doctors (provide json object in request body)

To update record of a doctor-->> PUT http://localhost:8080/medicare/api/doctors/1 (provide json object in request body)

To delete a single record -->> DELETE http://localhost:8080/medicare/api/doctors/1

To delete all records -->> DELETE http://localhost:8080/medicare/api/doctors
