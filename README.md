## YML File

```shell
mvn clean compile
```

## JSON
```json

```

|  #  | POM-Library | Client-Inports |
|:---:| :--- | :--- |
|  1  |feign|generates with feign libraries
|  2  |jersey1|import com.sun.jersey.*
|  3  |jersey2|import javax.ws.*
|  4  |jersey3|import jakarta.ws.*
|  5  |okhttp-gson|
|  5  |okhttp4-gson|
|  5  |retrofit|
|  5  |retrofit2|
|  5  |resttemplate|generates with spring boot binaries 
|  5  |resteasy|


## Errors
### Error
java.lang.RuntimeException: missing OpenAPI input!

### Solutions
in the input json replace ["swagger": "3.0.0",] with ["openapi": "3.0.2",]

