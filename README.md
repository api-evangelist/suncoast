# Suncoast Credit Union (suncoast)

Suncoast Credit Union is a state-chartered, federally insured (NCUA), member-owned not-for-profit financial cooperative headquartered in Tampa, Florida. Founded in 1934, it is the largest credit union in Florida and one of the largest in the United States, serving well over a million members with more than $17 billion in assets. It offers consumer and small-business deposit accounts, lending, cards, and digital banking.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/suncoast/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/suncoast/refs/heads/main/apis.yml)

## Open-Finance / API Posture

Suncoast Credit Union publishes **no first-party public developer API** and operates **no developer portal**. Probing confirmed that neither `developer.` nor `api.` subdomains resolve for `suncoastcreditunion.com` or `suncoast.com`, and there is no "Developers" or "API" surface on the marketing site. Digital banking runs on a hosted online/mobile platform at `banking.suncoastcreditunion.com`.

Consistent with most U.S. credit unions, consumer-permissioned data sharing is available only indirectly:

- **Aggregator access** — account data is reachable through third-party aggregators (Plaid, MX, Finicity, Akoya) and the institution's digital-banking core provider, not a direct first-party API.
- **FDX (Financial Data Exchange)** — no publicly documented FDX participation.
- **CFPB Section 1033** — no published open-banking / personal-financial-data-rights posture.

This is an honest identity-only record: **no public API, aggregator-only.**

## Tags

- Financial Services
- Banking
- United States
- Credit Union
- Florida
- Open Finance
- Data Aggregation

## Timestamps

- **Created:** 2026-07-23
- **Modified:** 2026-07-23

## APIs

None. Suncoast Credit Union exposes no public first-party API.

## Common Properties

- [Website](https://www.suncoastcreditunion.com/)
- [LinkedIn](https://www.linkedin.com/company/suncoastcreditunion/)
- [Online Banking Sign In](https://banking.suncoastcreditunion.com/)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
