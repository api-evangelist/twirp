# Twirp

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
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Twirp is a simple RPC framework built on Protocol Buffers, created by Twitch, that generates routing and serialization code from Protobuf service definitions for Go and other languages. Similar to gRPC but runs on the standard library's net/http server without custom transport implementations.

**Type:** Company (Open Source)  
**License:** Apache 2.0  
**Modified:** 2026-05-03

## Framework

### Twirp RPC Framework
Define your service in a .proto file and Twirp generates servers and clients implementing the Twirp wire protocol over HTTP. Uses POST requests with URLs in the form /twirp/[Package].[Service]/[Method]. Supports both Protobuf binary and JSON encoding.

**Human URL:** [https://twitchtv.github.io/twirp/](https://twitchtv.github.io/twirp/)

#### Tags

Protocol Buffers, RPC, Go, Code Generation

#### Properties

- [Documentation](https://twitchtv.github.io/twirp/docs/intro.html)
- [Getting Started](https://twitchtv.github.io/twirp/docs/install.html)
- [GitHub](https://github.com/twitchtv/twirp)
- [Wire Protocol](https://github.com/twitchtv/twirp/blob/main/PROTOCOL.md)

## Artifacts

### JSON Schemas

- [Twirp Error Schema](json-schema/twirp-error-schema.json)

### JSON Structures

- [Twirp Error Structure](json-structure/twirp-error-structure.json)

### JSON-LD

- [Twirp Context](json-ld/twirp-context.jsonld)

### Vocabulary

- [Twirp Vocabulary](vocabulary/twirp-vocabulary.yml)

## Common Properties

- [Website](https://twitchtv.github.io/twirp/)
- [Documentation](https://twitchtv.github.io/twirp/docs/intro.html)
- [GitHub Organization](https://github.com/twitchtv)
- [GitHub Repository](https://github.com/twitchtv/twirp)
- [Wire Protocol](https://github.com/twitchtv/twirp/blob/main/PROTOCOL.md)
- [License](https://github.com/twitchtv/twirp/blob/main/LICENSE)

## Tags

Protocol Buffers, RPC, Go, SDKs, Open Source, Protobuf

## Maintainers

**FN:** Kin Lane  
**Email:** kin@apievangelist.com
