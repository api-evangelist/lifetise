# Coadjute (lifetise)

Coadjute Ltd is a London-based property technology company that operates a shared network for the UK residential property market, connecting estate agents, conveyancers, mortgage brokers, lenders and consumers through the CRM and case-management systems they already use rather than through any multiple listing service — the UK has no MLS and no RESO adoption. Built on R3 Corda distributed ledger technology and now positioned as a fully managed AML and compliance platform for UK property, Coadjute sits in the middle of the transaction as connective infrastructure: property packs, material information, shareable AML checks and status data moving between parties. Its API posture is partner-only and not publicly reachable.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/lifetise/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/lifetise/refs/heads/main/apis.yml)

## Tags

- Real Estate
- United Kingdom
- PropTech
- Property Transactions
- Conveyancing
- AML
- Compliance
- Distributed Ledger
- Estate Agents
- Mortgage

## Timestamps

- **Created:** 2026-07-26
- **Modified:** 2026-07-26

## APIs

No publicly documented API is listed. Coadjute's own Partner Terms of Service govern "the Coadjute Applet, APIs, Connector, Sandbox, DLT Application" and its Network Acceptable Use Policy names a "Partner Cloud API" — so an API product exists — but the developer portal at `developer.coadjute.com` returns HTTP 502, `api.coadjute.com` answers only with authenticated JSON error envelopes, and no OpenAPI, OData `$metadata`, Postman collection or SDK is published. Access is by commercial partner agreement (Order Form + Subscription Term), not self-serve signup.

## Access and Standards Posture

- **Home market:** United Kingdom
- **RESO posture:** No RESO reference found — no Web API or Data Dictionary certification, no `$metadata`, no UPI. The UK has no MLS to certify against.
- **Access gate:** `partner-only` — a signed Coadjute Partner Terms of Service with an Order Form and Subscription Term; API tokens are provisioned by Coadjute support per partner.
- **Open data:** None. The open UK property-data layer belongs to HM Land Registry and Ordnance Survey, not Coadjute.
- **Auth model:** OAuth 2.0 / OpenID Connect via Auth0 (`https://auth.coadjute.com/`), plus manually issued partner API tokens.

## Properties

- [Website](https://www.coadjute.com/)
- [Authentication](authentication/coadjute-openid-configuration.json) — OpenID Connect discovery document, harvested verbatim 2026-07-26
- [Status Page](https://status.coadjute.com)
- [Partner Terms of Service](https://www.coadjute.com/coadjute-partner-terms-of-service)
- [Network Acceptable Use Policy](https://www.coadjute.com/coadjute-network-acceptable-use-policy)
- [Privacy Statement](https://www.coadjute.com/privacy-statement)
- [Pricing](https://www.coadjute.com/pricing)
- [Blog](https://www.coadjute.com/resources)
- [GitHub Organization](https://github.com/coadjute)
- [LinkedIn](https://www.linkedin.com/company/coadjute/)
- [Contact](https://www.coadjute.com/contact-us)

## Review

See [review.yml](review.yml) for the full probe log, RESO posture, access-gate evidence and auth-model findings.
