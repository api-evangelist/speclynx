# SpecLynx

Enterprise-ready API tooling for authors and maintainers of OpenAPI, AsyncAPI, and Arazzo specifications. Built by veterans with 15+ years of Swagger and OpenAPI development experience, SpecLynx provides semantic editing, real-time validation, and live preview — with an offline-first, zero-telemetry architecture that keeps your specs on your machine.

**URL:** [https://speclynx.com/](https://speclynx.com/)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

API Design, AsyncAPI, Developer Tools, JSON Schema, OpenAPI, Toolkit, VSCode

## Timestamps

- **Created:** 2026-01-02
- **Modified:** 2026-05-02

## Products

| Product | Type | Description |
|---|---|---|
| [OpenAPI Toolkit](https://speclynx.com/openapi-toolkit/) | VS Code Extension | Semantic editing, validation, live preview for OpenAPI/AsyncAPI/Arazzo |
| [SpecLynx Editor](https://speclynx.com/editor/) | Browser Tool | Client-side OpenAPI editor at editor.speclynx.com |
| [SpecLynx CLI](https://speclynx.com/) | CLI | Overlay operations, dereferencing, bundling, format conversion |
| [Language Service](https://speclynx.com/language-service/) | npm Library | LSP-compatible library with 13 editing capabilities |
| [ApiDOM](https://speclynx.com/apidom/) | Parsing Engine | Semantic parser powering all SpecLynx products |

## Supported Formats

| Format | Versions |
|---|---|
| OpenAPI | 2.0, 3.0.x, 3.1.x |
| AsyncAPI | 2.x |
| Arazzo | 1.x |
| JSON Schema | Draft 4/5, 6, 7, 2019-09, 2020-12 |

## Artifacts

### JSON Schema

- [speclynx-validation-result-schema.json](json-schema/speclynx-validation-result-schema.json) — Schema for diagnostic results from SpecLynx validation
- [speclynx-completion-item-schema.json](json-schema/speclynx-completion-item-schema.json) — Schema for autocompletion items from the Language Service

### JSON Structure

- [speclynx-product-structure.json](json-structure/speclynx-product-structure.json) — Structure of the SpecLynx product ecosystem and component relationships

### JSON-LD

- [speclynx-context.jsonld](json-ld/speclynx-context.jsonld) — JSON-LD context mapping SpecLynx vocabulary to linked data semantics

### Examples

- [speclynx-validation-result-example.json](examples/speclynx-validation-result-example.json) — Example validation results from SpecLynx checking an OpenAPI 3.1 spec

### Vocabulary

- [speclynx-vocabulary.yml](vocabulary/speclynx-vocabulary.yml) — Domain vocabulary for SpecLynx concepts including ApiDOM, Language Service, semantic validation, and editing features

## Resources

- [Website](https://speclynx.com/)
- [OpenAPI Toolkit Documentation](https://speclynx.com/openapi-toolkit/)
- [VS Code Marketplace](https://marketplace.visualstudio.com/items?itemName=SpecLynx.vscode-openapi-toolkit)
- [Open VSX Registry](https://open-vsx.org/extension/SpecLynx/vscode-openapi-toolkit)
- [GitHub Repository](https://github.com/speclynx/vscode-openapi-toolkit)
- [Browser Editor](https://editor.speclynx.com/)
- [Contact](mailto:info@speclynx.com)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
