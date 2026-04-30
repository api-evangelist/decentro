# Decentro (decentro)

Decentro is a banking-as-a-service platform that provides businesses with seamless integration to Indian banking infrastructure - including payments (UPI, IMPS, NEFT, RTGS), virtual accounts, KYC, ledger primitives, and credit-bureau data.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/decentro/refs/heads/main/apis.yml)

## Scope

- **Type:** Contract
- **Position:** Consuming
- **Access:** 3rd-Party
- **x-type:** company

## Tags

- Banking, Banking-as-a-Service, FinTech, India, KYC, Ledger, Payments, UPI, Virtual Accounts

## Timestamps

- **Created:** 2025-02-24
- **Modified:** 2026-04-28

## APIs

### Decentro KYC & Onboarding API

Identity verification, customer onboarding, DigiLocker integration, Aadhaar OTP, document classification, and face match.

- **Base URL:** https://in.decentro.tech
- **Human URL:** https://docs.decentro.tech/

#### Properties

- [Documentation](https://docs.decentro.tech/)
- [OpenAPI](openapi/decentro-kyc-api-openapi.yml)

### Decentro Payments API

Collections, payouts, ENACH mandates, UPI Autopay, settlements, and refunds for the Indian banking system.

- **Base URL:** https://in.decentro.tech
- **Human URL:** https://docs.decentro.tech/

#### Properties

- [Documentation](https://docs.decentro.tech/)
- [OpenAPI](openapi/decentro-payments-api-openapi.yml)
- [JSONSchema - Payout](json-schema/decentro-payout.json)
- [Rules](rules/decentro-payments-api-rules.yml)
- [Capabilities](capabilities/decentro-payments-api-capabilities.yml)

### Decentro Virtual Accounts API

Create and manage virtual bank accounts, balances, statements, and remitter whitelisting for collections and reconciliation.

- **Base URL:** https://in.decentro.tech
- **Human URL:** https://docs.decentro.tech/

#### Properties

- [Documentation](https://docs.decentro.tech/)
- [OpenAPI](openapi/decentro-virtual-accounts-api-openapi.yml)
- [JSONSchema - Virtual Account](json-schema/decentro-virtual-account.json)

### Decentro Ledger API

Double-entry accounting primitives for journals, ledger accounts, and transactions tied to Decentro virtual accounts and external counterparties.

- **Base URL:** https://in.decentro.tech
- **Human URL:** https://docs.decentro.tech/

#### Properties

- [Documentation](https://docs.decentro.tech/)
- [OpenAPI](openapi/decentro-ledger-api-openapi.yml)

## Common Properties

- [Website](https://decentro.tech/)
- [Portal](https://docs.decentro.tech/)
- [Reference](https://docs.decentro.tech/reference)
- [Blog](https://decentro.tech/blog/)
- [JSON-LD](json-ld/decentro-context.jsonld)
- [Vocabulary](vocabulary/decentro-vocabulary.yml)

## Maintainers

- **Kin Lane** - kin@apievangelist.com
