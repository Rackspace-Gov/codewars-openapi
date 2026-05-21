
[![chat](https://img.shields.io/gitter/room/noid-dev/community?color=49c39e)](https://gitter.im/noid-dev/community)

Welcome aboard fellow developer, this is where you will find the OAS
for [Codewars' public API](https://dev.codewars.com).

## What is OAS?

The OpenAPI Specification (OAS) defines a standard, language-agnostic interface to HTTP APIs which
allows both humans and computers to discover and understand the capabilities of the service
without access to source code, documentation, or through network traffic inspection. When properly
defined, a consumer can understand and interact with the remote service with a minimal amount of
implementation logic.

An OpenAPI definition can then be used by documentation generation tools to display the API, code
generation tools to generate servers and clients in various programming languages, testing tools,
and many other use cases.

-- <cite>[OpenAPI Initiative (OAI)][1]</cite>

## Project Status

The Codewars OpenAPI Specification is currently in Early Availability. While the specification
should be accurate, it is under active development. The structure of this repository may continue to
evolve. If you encounter any inaccuracies or have feedback on how it can better suite your use case,
please [open an issue](https://github.com/noid-dev/codewars-openapi/issues/new) to let us know.

## Development

To generate a bundled version of the specification locally, run:

> npm run build

To preview the documentation locally, run:

> npm start

The documentation will be available at: http://127.0.0.1:8080

[1]: https://spec.openapis.org/oas/latest.html
