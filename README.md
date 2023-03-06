# json-versioning

Having two or more JSON Schema, that have an unique "version" number, we want our data to be valid against a `main` JSON Schema.

The JSON data schall be validated against `schema.json`, which has logic to determine the right JSON Schema (depending on the provided version).
