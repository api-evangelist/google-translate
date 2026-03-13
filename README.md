# Google Cloud Translation API

The Google Cloud Translation API provides programmatic access to Google's neural machine translation technology. It enables developers to dynamically translate text between thousands of language pairs, detect the source language of text, and retrieve lists of supported languages. The API supports both basic (v2) and advanced (v3) translation capabilities including batch translation, custom models, glossaries, and adaptive translation.

## Artifacts

- **APIs.yml** - Machine-readable API metadata following the APIs.json specification.
- **OpenAPI** (`openapi/openapi.yml`) - OpenAPI 3.1.0 specification describing the Cloud Translation API endpoints, parameters, and response schemas.
- **JSON Schema** (`json-schema/google-translate.json`) - JSON Schema (draft 2020-12) defining request and response objects for the Translation API.
- **JSON-LD** (`json-ld/google-translate.jsonld`) - JSON-LD context mapping Translation API terms to schema.org and API-specific vocabularies.

## Key Endpoints

| Method | Path | Description |
|--------|------|-------------|
| POST | `/language/translate/v2` | Translate text between languages |
| POST | `/language/translate/v2/detect` | Detect the language of text |
| GET | `/language/translate/v2/languages` | List supported languages |

## Resources

- [API Documentation](https://cloud.google.com/translate/docs)
- [Getting Started](https://cloud.google.com/translate/docs/setup)
- [Pricing](https://cloud.google.com/translate/pricing)
- [API Reference](https://cloud.google.com/translate/docs/reference/rest)

## Maintainer

Kin Lane - kin@apievangelist.com
