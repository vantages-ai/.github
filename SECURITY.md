# Security & Responsible Disclosure Policy (`vantages-ai`)

## Reporting a Security or Governance Integrity Issue

If you discover a security vulnerability, manifest verification bypass, or cryptographic receipt integrity flaw in any public repository under `github.com/vantages-ai`:

1. **Do NOT open a public GitHub Issue** containing exploit payloads, private keys, or customer endpoint details.
2. **Email our security & compliance contact:** `hello@vantages.app` with subject `[SECURITY] <repo-name> — <summary>`.
3. **Include:**
   - Target repository and commit SHA or Living Passport URL (`https://vantages.app/showcase/<app_id>`).
   - Steps to reproduce or unexpected `X-VOS-Interlock` / `checks 7/7` output.

## Key Security Invariants

- **Zero Secrets in Public Repositories:** All public templates (`vantages-ai/governance-evidence`, `vantages-ai/acta-remix`) must contain strictly zero API tokens, passwords, or private signing keys.
- **Fail-Closed Drift Detection:** Any mismatch against anchored RFC 8785 digests switches public badges fail-closed to `VOIDED_ON_DRIFT` until Article 14 human re-review (`Role >= 40`) completes.
- **No Self-Sealing:** Automated scripts or Contributor bots (`Role <= 20`) cannot mint cryptographic seals or self-merge governance Pull Requests.
