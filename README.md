# COP Data API Specification

> The API specification for the COP Data API (which also includes a mock server)

## Developing the API specification

This project uses the [OpenAPI 3.0](https://github.com/OAI/OpenAPI-Specification/blob/master/versions/3.0.0.md) standard to document the Operational Data Service API.

## Viewing the API specification

You can view the Swagger spec in a local Swagger docker container by running the following command, from this project's directory:

```
docker run -p 80:8080 -e SWAGGER_JSON=/tmp/swagger.yml -v `pwd`:/tmp swaggerapi/swagger-ui
```

After making changes to the `swagger.yml` you will need to refresh your browser to see the updates (there is no need to restart the Docker container).

This swagger documentation can be found at:
https://data-api-spec.dev.cop.homeoffice.gov.uk/
