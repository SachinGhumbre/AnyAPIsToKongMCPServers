# Any APIs to Kong MCP Servers

## Transform Any Enterprise API into AI-Native MCP Servers on Kong Gateway

**Powered by Kong Gateway, Kong Konnect, deck CLI and AI MCP Proxy**

Any APIs to Kong MCP Servers is an enterprise-grade automation platform that converts APIs into AI-ready Model Context Protocol (MCP) servers running on Kong Gateway. The platform supports OpenAPI specifications, existing Kong Gateway configurations, enterprise APIs, partner APIs, legacy services, and third-party APIs.

## Vision

Enable every enterprise API to become AI-accessible.

The platform acts as an AI Enablement Factory for Kong Gateway by automatically transforming APIs into MCP-compatible tools that can be discovered and invoked by AI assistants, AI agents, and agentic workflows without backend code changes.

## Key Capabilities

- OpenAPI Specification to MCP Server
- Existing Kong Configuration to MCP Server
- Kong Konnect Integration
- Automated ai-mcp-proxy Configuration
- MCP Listener Generation
- deck Validation, Diff and Sync
- Enterprise Governance and Security

## Supported Sources

- OpenAPI Specifications
- Existing Kong Gateway Configurations
- Enterprise REST APIs
- Microservices APIs
- Legacy APIs
- SaaS APIs
- Partner APIs
- Third-Party APIs

## Business Value

- Transform APIs into MCP tools in minutes
- Accelerate Agentic AI adoption
- Preserve Kong security controls
- Reuse existing Kong investments
- Enable AI self-service discovery
- Standardize AI integration patterns
- Scale AI enablement across thousands of APIs

## Architecture Flow

Enterprise APIs → Kong Gateway → ai-mcp-proxy → MCP Servers → AI Agents

## Deployment Tag Strategy

```yaml
tags:
  - AnyAPIsToKongMCPServers
  - mcp-tools
```

```bash
deck gateway diff --select-tag AnyAPIsToKongMCPServers
deck sync --select-tag AnyAPIsToKongMCPServers
```

## Tool Overview

The platform automates:

1. API Discovery
2. Kong Configuration Generation
3. MCP Plugin Injection
4. MCP Listener Creation
5. Validation
6. Deployment to Konnect
7. MCP Testing

## Generated Components

- Kong Services
- Kong Routes
- ai-mcp-proxy Plugins
- MCP Listener Routes
- Deployment Packages
- Validation Reports
- Konnect Deployment Assets

## Positioning Statement

Any APIs to Kong MCP Servers is an enterprise-grade automation platform that transforms any API managed through Kong Gateway into AI-native MCP servers. The platform supports OpenAPI specifications, existing Kong configurations, internal enterprise APIs, partner APIs, and legacy services, automatically generating MCP-enabled Kong configurations using Kong's native ai-mcp-proxy plugin and deploying them through Kong Konnect and deck CLI.
