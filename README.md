SEW | CORE | Validation

## User Story 1
*As a musician I want the system to notify me about possible mistakes, so that the data in the database is consistent.*

### Acceptance Criteria
- All fields in the editor are using validation.
- Feedback about validation issues are displayed to the user.
- Validation is performed on the server and on the client (using [vuelidate](https://vuelidate-next.netlify.app/)).

### Hint
- To use the full range of the spring boot validation system add the following lines to your pom.xml and let maven update your project.
```
<dependency> 
  <groupId>org.springframework.boot</groupId> 
  <artifactId>spring-boot-starter-validation</artifactId> 
</dependency>
```
