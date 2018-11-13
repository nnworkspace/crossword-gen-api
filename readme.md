# crossword-gen-api

This project simply provides an OpenAPI (formerly known as Swagger) document and a Gradle build
script for generating server and client sub for it.

I use this as an example for other projects that need the OpenAPI-Generator integration. You may
edit the `build.gradle` file to fit your need.

## Usage:

```
gradlew codegen

```

To view all possible clients and servers:

```
gradlew openApiGenerators
```


## References:

https://github.com/OpenAPITools/openapi-generator

https://github.com/OpenAPITools/openapi-generator/tree/master/modules/openapi-generator-gradle-plugin