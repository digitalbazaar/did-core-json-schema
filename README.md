# [DID Core](https://w3.org/TR/did-core/) JSON Schema

[JSON Schema](https://json-schema.org/) for validating
[DID Core](https://w3.org/TR/did-core/)-based JSON and JSON-LD documents.

## Files

`did-core.json` is the JSON Schema file.
`examples/` contains example `.didjson` files extracted from the DID Core
specification and validated against the `did-core.json` schema.

Any example ending in `.didjson` is validate-able with the the `did-core.json`
JSON Schema.

Any example ending in `.jwt` or `.jwe` are _not_ directly validate-able as the
DID document is embedded in the JWT format.

## License

[BSD-3-License](LICENSE) Copyright 2024 Digital Bazaar, Inc.
