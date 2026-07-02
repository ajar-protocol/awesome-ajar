# awesome-ajar - Ajar Directory

A PR-driven directory for Ajar implementations, integrations, tools, bridges, and conformant sites. Third-party entries are expected and encouraged.

## Sections (grow by PR)
### Specifications & core
- [ajar](https://github.com/ajar-protocol/ajar): protocol spec
- [conformance](https://github.com/ajar-protocol/conformance): compatibility suite

### Implementations
- **Servers/Gateways:** [ajar-gateway](https://github.com/ajar-protocol/ajar-gateway) (reference, Rust) · *yours here*
- **Clients/Kernels:** `ajar-kernel` (reference, publishes at Phase 2) · *yours here*

### Platform integrations
- `ajar-woocommerce` (publishes at Stage 4) · `ajar-shopify` (publishes at Stage 4) · *your CMS/host/framework here*

### Bridges & interop
- MCP surface in the Kernel
- Planned: WebMCP, NLWeb, ACP/UCP commerce bindings, A2A, x402/AP2 settlement adapters. See [planning/POSITIONING.md](https://github.com/ajar-protocol/planning/blob/main/POSITIONING.md).

### Tools
- [ajar-docs-mcp](https://github.com/ajar-protocol/ajar-docs-mcp): Ajar spec access for coding agents
- *validators, manifest generators, dashboards here*

### Conformant sites in the wild
- Initial entries will come from `ajar-examples` deployments (publishes across Phases 1-3 demos).

### Learning
- [planning/INTEGRATION-STORIES.md](https://github.com/ajar-protocol/planning/blob/main/INTEGRATION-STORIES.md) · demo benchmark reports (as published)

## Listing criteria
Implementations must publish a conformance report; see `conformance/REPORTS.md` once the harness lands. Sites must pass the public conformance check for their claimed profiles. Tools and bridges need a working README and license. Closed-source and commercial entries use the same criteria.

## License

This directory is licensed under CC-BY-4.0. See `LICENSE`.
