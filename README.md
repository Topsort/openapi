# Topsort OpenAPI

Topsort uses the [OpenAPI 3.1.0](https://github.com/OAI/OpenAPI-Specification/blob/main/versions/3.1.0.md) specification to [document our APIs](https://docs.topsort.com) and we recommend our clients to use these specifications to generate supported client libraries and server scaffolding. This would provide a consistent and robust developer experience across languages.

## Validating the file

- Use [prettier](https://prettier.io/) to format the documents: `bunx prettier -w`
- Use [yamllint](https://github.com/adrienverge/yamllint) to validate the documents: `uvx yamllint *.yml`

## Using the OpenAPI generator

You can find examples on the official [OpenAPI Generator docs](https://openapi-generator.tech/docs/usage#examples).
