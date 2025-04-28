# OpenAPI Specification for the Model Repository API Client

This API provides access to the REFORMERS Digital Twin Model Repository.
Use [Redocly CLI](https://redocly.com/docs/cli) for validating the API and generating the docs.

## API Validation

Linux:
``` shell
docker run --rm -v ${PWD}:/spec redocly/cli lint openapi.yaml
```

Windows:
``` batchfile
docker run --rm -v %cd%:/spec redocly/cli lint openapi.yaml
```

## Build API Domumentation

Linux:
``` shell
docker run --rm -v ${PWD}:/spec redocly/cli build-docs openapi.yaml -o docs/reformers-dt-repository-api.html
```

Windows:
``` batchfile
docker run --rm -v %cd%:/spec redocly/cli build-docs openapi.yaml -o docs/reformers-dt-repository-api.html
```

## Bundle OpenAPI to a single file

Linux:
``` shell
docker run --rm -v ${PWD}:/spec redocly/cli bundle openapi.yaml -o bundled.yaml
```

Windows:
``` batchfile
docker run --rm -v %cd%:/spec redocly/cli bundle openapi.yaml -o bundled.yaml
```
