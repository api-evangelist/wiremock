# WireMock

WireMock is an open source tool for mocking HTTP services and APIs. It enables developers to build stable, predictable development environments by creating mock APIs that simulate the behavior of real services. WireMock provides a comprehensive admin API for managing stub mappings, recording real traffic, verifying requests, and modeling stateful behavior through scenarios.

**Website:** [https://wiremock.org/](https://wiremock.org/)
**Documentation:** [https://wiremock.org/docs/](https://wiremock.org/docs/)
**GitHub:** [https://github.com/wiremock](https://github.com/wiremock)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

API Mocking, Mock Server, Mocking, Platform, Stubs, Testing

## Timestamps

- **Created:** 2025-01-08
- **Modified:** 2026-05-03

## APIs

### WireMock Admin API

The WireMock Admin REST API provides programmatic control over a running WireMock server instance. It supports creating, updating, and deleting stub mappings; querying the request journal; recording and replaying real API traffic; managing stateful scenarios; and performing system operations such as reset and shutdown.

**Human URL:** [https://wiremock.org/docs/standalone/admin-api-reference/](https://wiremock.org/docs/standalone/admin-api-reference/)
**Base URL:** `http://localhost:8080/__admin/`

**Tags:** Admin API, API Mocking, Mock Server, Stub Management, Testing

**Properties:**
- [Documentation](https://wiremock.org/docs/standalone/admin-api-reference/)
- [OpenAPI Spec](openapi/wiremock-admin-api-openapi.yml)
- [Spectral Rules](rules/wiremock-rules.yml)
- [Capabilities](capabilities/api-mocking-and-testing.yaml)

## Common Properties

- [Website](https://wiremock.org/)
- [Documentation](https://wiremock.org/docs/)
- [Admin API Reference](https://wiremock.org/docs/standalone/admin-api-reference/)
- [GitHub Repository](https://github.com/wiremock/wiremock)
- [GitHub Organization](https://github.com/wiremock)

## SDKs

| Language | Repository |
|----------|------------|
| Java | [wiremock/wiremock](https://github.com/wiremock/wiremock) |
| Python | [wiremock/python-wiremock](https://github.com/wiremock/python-wiremock) |
| JavaScript | [wiremock/wiremock-js](https://github.com/wiremock/wiremock-js) |
| .NET | [wiremock/WireMock.Net](https://github.com/wiremock/WireMock.Net) |
| Go | [wiremock/go-wiremock](https://github.com/wiremock/go-wiremock) |
| PHP | [wiremock/wiremock-php](https://github.com/wiremock/wiremock-php) |
| Kotlin | [wiremock/kotlin-wiremock](https://github.com/wiremock/kotlin-wiremock) |

## Artifacts

### OpenAPI Specifications

| Spec | Description |
|------|-------------|
| [WireMock Admin API](openapi/wiremock-admin-api-openapi.yml) | OpenAPI 3.0 spec for the WireMock Admin REST API |

### Spectral Rules

| Ruleset | Description |
|---------|-------------|
| [WireMock Rules](rules/wiremock-rules.yml) | Spectral rules enforcing WireMock Admin API conventions |

### Naftiko Capabilities

| Capability | Description |
|------------|-------------|
| [API Mocking and Testing](capabilities/api-mocking-and-testing.yaml) | Workflow capability for API mocking, stub management, and test verification |
| [Shared: WireMock Admin](capabilities/shared/wiremock-admin.yaml) | Per-API consumed definition for WireMock Admin API |

### JSON Schema

| Schema | Description |
|--------|-------------|
| [Stub Mapping Schema](json-schema/wiremock-stub-mapping-schema.json) | JSON Schema for a WireMock stub mapping object |

### JSON Structure

| Structure | Description |
|-----------|-------------|
| [Stub Mapping Structure](json-structure/wiremock-stub-mapping-structure.json) | Field-level documentation for stub mapping objects |

### JSON-LD

| Context | Description |
|---------|-------------|
| [WireMock Context](json-ld/wiremock-context.jsonld) | JSON-LD context for WireMock domain vocabulary |

### Examples

| Example | Description |
|---------|-------------|
| [Create Stub Mapping](examples/wiremock-create-stub-mapping-example.json) | Example stub mapping with request matching and response definition |
| [Scenario Stub Mapping](examples/wiremock-scenario-stub-example.json) | Example stateful scenario stub mapping |

### Vocabulary

| Vocabulary | Description |
|------------|-------------|
| [WireMock Vocabulary](vocabulary/wiremock-vocabulary.yml) | Domain vocabulary for API mocking, stub mapping, scenarios, and recording concepts |

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
