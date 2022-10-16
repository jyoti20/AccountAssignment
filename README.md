# AccountTransfer microservice
## This service is used to transfer money from one account to other.
### Project Structure



### Pre requisite (Java 8 +,maven 3+ ,mysql/h2 )

### Steps
#### Clone https://github.com/jyoti20/AccountAssignment.git
#### Import as maven project
#### run mvn clean Install -DskipTests or mvn clean Install command
#### run AccountServiceApplication.java will start spring boot application on 8080 port

#### Test Actuators after application up http://localhost:8080/actuator/health

#### Test Swagger link http://localhost:8080/swagger-ui/



## Create Account
###1:- Create Account
#### Api :- http://localhost:8080/save/account




###2:- Get Accounts
#### Api :- http://localhost:8080/getAccounts



###3. Get Account Details for a giiven account number

## checkout api
###1:- Call http://localhost:8080/getAccount/{accountNumber}



### Sonar Scan result :- Zero issue left , all resolved



### Unit Test case and Code Coverage result
Note:- 60% current coverage can extend >80 %
(Due to less time not able to cover all code).



### Dockerized (see Docker file in classpath) :- Can be improved
#### docker build -t invoice.
#### docker run -p 8080:8080 -t invoice

### Postman Collection attached(see in classpath)
File AccountApi.postman_collection.json


