# Apache Thrift

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

Apache Thrift is a cross-language RPC framework originally developed at Facebook for scalable cross-language services development. It provides a lightweight, language-independent software stack for point-to-point RPC implementation with clean abstractions for data transport, serialization, and application-level processing. The framework includes an Interface Definition Language (IDL) compiler that generates client and server code for 28+ programming languages including C++, Java, Python, Go, Ruby, PHP, Node.js, C#, and many others, enabling seamless cross-language service communication.

- **Human URL:** [https://thrift.apache.org/](https://thrift.apache.org/)
- **GitHub:** [https://github.com/apache/thrift](https://github.com/apache/thrift)
- **Version:** 0.23.0

## Description

Apache Thrift is a lightweight, language-independent software stack for point-to-point RPC implementation. It provides abstractions for data transport, serialization, and application-level processing with a code generation engine that produces client and server code for 28+ programming languages from a simple Interface Definition Language (IDL) definition. Thrift supports backward and forward compatibility through non-atomic version changes and is widely used for building high-performance cross-language microservices.

## Links

- [Documentation](https://thrift.apache.org/docs/)
- [Getting Started](https://thrift.apache.org/tutorial/)
- [Download](https://thrift.apache.org/download)
- [IDL Specification](https://thrift.apache.org/docs/idl)
- [Language Support](https://thrift.apache.org/docs/Languages)
- [Changelog](https://github.com/apache/thrift/blob/master/CHANGES.md)
- [Mailing List](https://thrift.apache.org/mailing)
- [Issue Tracker](https://issues.apache.org/jira/projects/THRIFT)

## Packages

- [npm](https://www.npmjs.com/package/thrift)
- [Maven (libthrift)](https://mvnrepository.com/artifact/org.apache.thrift/libthrift)
- [PyPI](https://pypi.org/project/thrift/)
- [Packagist](https://packagist.org/packages/apache/thrift)

## Artifacts

### JSON Schema

| File | Description |
|------|-------------|
| [thrift-idl-schema.json](json-schema/thrift-idl-schema.json) | JSON Schema for Apache Thrift IDL definitions covering structs, services, enums, exceptions, unions, and all IDL constructs |

### JSON Structure

| File | Description |
|------|-------------|
| [thrift-idl-structure.json](json-structure/thrift-idl-structure.json) | Structured documentation of all Apache Thrift IDL entity types and their fields |

### JSON-LD Context

| File | Description |
|------|-------------|
| [thrift-context.jsonld](json-ld/thrift-context.jsonld) | JSON-LD context mapping Thrift IDL vocabulary to linked data semantics |

### Examples

| File | Description |
|------|-------------|
| [thrift-calculator-service-example.json](examples/thrift-calculator-service-example.json) | Complete example of the classic Calculator service IDL in JSON representation |
| [thrift-client-server-example.json](examples/thrift-client-server-example.json) | Examples of client/server configuration for multiple languages with transport and protocol options |

### Vocabulary

| File | Description |
|------|-------------|
| [thrift-vocabulary.yml](vocabulary/thrift-vocabulary.yml) | Normative vocabulary for Apache Thrift covering IDL types, transports, protocols, servers, and code generation concepts |

## Supported Languages

C, C++, C#, Common Lisp, D, Dart, Delphi, Erlang, Go, Haxe, Java, JavaScript, Lua, Node.js, .NET Standard, OCaml, Perl, PHP, Python, Ruby, Rust, Smalltalk, Swift

## Tags

Apache, Code Generation, Cross Language, IDL, Open Source, RPC, SDKs, Serialization, Thrift
