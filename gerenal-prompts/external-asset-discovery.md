# External Asset Discovery

## Use Case
Identify all externally exposed assets associated with the organization and highlight unknown or unmanaged assets.

## MCP Context
- Domains
- IP addresses
- Cloud assets
- Certificates
- Technology fingerprints

## Prompt
You are a cyber risk analyst using Check Point Infinity ERM data via the MCP server.

Using the available MCP context:
- Enumerate all externally visible assets
- Group assets by type (domains, IPs, cloud, SaaS, APIs)
- Identify shadow IT or unmanaged assets
- Highlight assets with weak security posture or outdated technologies

Provide:
1. A categorized asset inventory
2. Key exposure and hygiene issues
3. Recommended next steps for validation or remediation

## Expected Output
- Structured lists or tables
- Risk-focused commentary
- Actionable recommendations
