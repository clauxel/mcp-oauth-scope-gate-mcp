# MCP OAuth Scope Gate

Review OAuth scopes for remote MCP servers before tokens are granted.

Paid remote MCP for OAuth scope risk inspection, approval routing, consent receipts, server policy validation, and scope audit exports.

## Public Endpoints

- Website: https://mcpoauthscopegate.clauxel.com/?utm_source=github&utm_medium=directory&utm_campaign=sbl202605
- MCP endpoint: https://mcpoauthscopegate.clauxel.com/mcp
- Server card: https://mcpoauthscopegate.clauxel.com/server-card.json
- Registry name: `com.clauxel.mcpoauthscopegate/mcpoauthscopegate-mcp`

## Access

This is a paid hosted remote MCP. Production calls require a bearer token issued from the product website.

```http
Authorization: Bearer <token>
```

Unauthenticated browser visits to `/mcp` return a clear JSON error instead of internal details.

## Tools

- `inspect_oauth_scope_risk`
- `request_scope_approval`
- `issue_consent_receipt`
- `validate_server_scope_policy`
- `export_scope_audit`

## Quick Start

1. Open the website and choose a plan.
2. Create or request an API token.
3. Add the endpoint to an MCP client that supports Streamable HTTP remote servers.
4. Send JSON-RPC requests with the bearer token.

## Useful Links

- Product page: https://mcpoauthscopegate.clauxel.com/?utm_source=github&utm_medium=directory&utm_campaign=sbl202605
- Pricing: https://mcpoauthscopegate.clauxel.com/?utm_source=github&utm_medium=directory&utm_campaign=sbl202605#pricing
- Server card: https://mcpoauthscopegate.clauxel.com/server-card.json
- MCP endpoint: https://mcpoauthscopegate.clauxel.com/mcp

## Status

This repository is a public documentation and directory-submission reference for the hosted service. It does not contain the private production source code.
