# Topsort OpenAPI

Topsort uses the [OpenAPI 3.1.0][openapi] specification to [document our APIs][docs] and we
recommend our clients to use these specifications to generate supported client libraries and server
scaffolding. This would provide a consistent and robust developer experience across languages.

You can additionally consume the entire Topsort OpenAPI spec available [here][openapi-ts].

## Validating the file

- Use [prettier][prettier] to format the documents: `bunx prettier -w`
- Use [yamllint][yamllint] to validate the documents: `uvx yamllint *.yml`
- Use [vacuum][vacuum] to validate the openapi standard: `vacuum *.yml`
- Use [redocly][redocly] to further validate the openapi standard: `bunx @redocly/cli lint *.yml`
- Use [typos][typos] to fix language typos: `typos .`

## Using the OpenAPI generator

You can find examples on the official
[OpenAPI Generator docs](https://openapi-generator.tech/docs/usage#examples).

[openapi]: https://spec.openapis.org/oas/v3.1.0.html
[docs]: https://docs.topsort.com
[openapi-ts]: https://docs.topsort.com/openapi.json
[prettier]: https://prettier.io/
[yamllint]: https://github.com/adrienverge/yamllint
[vacuum]: https://quobix.com/vacuum/start/
[redocly]: https://redocly.com/docs/cli/installation
[typos]: https://github.com/crate-ci/typos
