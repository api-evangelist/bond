# Bond

Bond Financial Technologies is a US banking-as-a-service (BaaS) and embedded-finance platform that lets software companies and fintechs embed deposit accounts, card issuing, money movement, credit, and identity verification into their apps through a single REST API. Bond was acquired by FIS in June 2023; its developer documentation remains live at [docs.bond.tech](https://docs.bond.tech/reference/intro).

This API Evangelist profile enriches the original portfolio-lead stub into nine real documented API product families harvested from Bond's public developer docs:

- Customers & KYC
- Businesses & KYB (beneficial owners)
- Cards (issuing, restrictions, PCI web SDK)
- Accounts & Statements
- Transfers (ACH, account-to-account, Plaid external accounts)
- Ledger / Transactions
- Credit (credit-builder + secured charge)
- Webhooks
- Simulation (sandbox)

Authentication is API-key based (`Identity` + `Authorization` headers). No single downloadable OpenAPI is published — the ReadMe HTML reference and a public Postman workspace are the machine-readable surfaces. See `review.yml` for the full reviewer finding.

Backed by: canaan-partners
