# FlatPeak OpenAPI Specification

This repository contains [OpenAPI specifications][openapi] for FlatPeak API.

Files can be found in the `openapi/` directory:

* `flatpeak-api-spec.json:` OpenAPI 3.0 spec matching the public FlatPeak API.

The specs provided in this repository do not explicity target [openapi-generator](https://github.com/OpenAPITools/openapi-generator). They are instead generated via a custom closed-source generator.

## Vendor Extensions

The specification ships with a few vendor-specific fields to help represent information in ways that are difficult in OpenAPI by default.
