# SpecLynx

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

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
