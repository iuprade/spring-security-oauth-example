## Spring Security OAuth


### Build the Project
```
mvn clean install
```

### Notes

- This project consists of 2 main sub-modules, each sub-module is a Spring Boot Application running on specific port
    - spring-security-oauth-server       (port = 8081)
    - spring-security-oauth-resource     (port = 8082)

- To run the project, run both _spring-security-oauth-server_ and _spring-security-oauth-resource_ first - then run  the UI modules

- You can run any sub-module using command line: 
```
mvn spring-boot:run
```

```
- To run Angular4 front-end modules (_spring-security-oauth-ui-password-angular4_) , we need to build the app first:
```
mvn clean install
```
Then we need to navigate to our Angular app directory:
```
cd src/main/resources
```
Finally, we will start our app:
```
npm start
```


