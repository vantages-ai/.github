# Contributing to `vantages-ai` Public Repositories

Thank you for contributing to the **Vantages Applied AI** (`VOS Acta V4`) public governance ecosystem.

## Governance & Contribution Rules

1. **Two-Repository Roles:**
   - [`vantages-ai/governance-evidence`](https://github.com/vantages-ai/governance-evidence): Starter evidence template repository for AI deployers.
   - [`vantages-ai/acta-remix`](https://github.com/vantages-ai/acta-remix): Public Cookbook remediation recipes (55 canonical manifests) and governance gap triage hub.
2. **Mandatory Verification Gates Before PR Review:**
   - For `governance-evidence`: `node scripts/verify-governance-evidence.mjs` must report `7/7 PASS`.
   - For `acta-remix`: `node scripts/verify-remix-catalog.mjs` must report `55/55 PASS`.
3. **Article 14 Human Oversight & Zero Autonomous Merge:**
   - Automated bots (`@acta-remix` / `emdash-bot`) never self-merge Pull Requests or restore revoked seals.
   - Every remediation Pull Request requires explicit human reviewer verification (`Role >= 40`) and accurate `NOT_CHECKED` negative-fact disclosures.
4. **English SSoT & Safe Claims:**
   - All public documentation and templates must use plain English and include non-legal attestation notices (process attestation only, not legal certification).
