# Apache Thrift

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
