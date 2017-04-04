# sympa-spec-openapi
the swagger specification of the REST API

## generate the json file
  Install and use [swagger-codegen](https://github.com/swagger-api/swagger-codegen):

  ```bash
  cd swagger
  swagger-codegen generate -i sympa-api.yaml -l swagger && mv swagger.json sympa-api.json
  ```

