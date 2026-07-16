# Security Policy

Pacta handles escrow, collateral, and trust decisions, so we take security seriously
and appreciate responsible disclosure.

## Reporting a vulnerability

**Please do not open a public issue for security vulnerabilities.** Public disclosure
before a fix puts users at risk.

Report privately through either channel:

- **GitHub private advisory** (preferred): on the affected repository, go to the
  **Security** tab → **Report a vulnerability**. This opens a private thread with the
  maintainers.
- **Email**: **hello@pactaprotocol.org**

Please include, as far as you can:

- the affected repository and version/commit,
- a description of the issue and its impact,
- steps to reproduce or a proof of concept,
- any suggested remediation.

## What to expect

- We aim to acknowledge your report within **72 hours**.
- We will keep you updated as we investigate and work on a fix.
- We will credit you in the advisory once the issue is resolved, unless you prefer to
  remain anonymous.

## Scope

In scope: the protocol implementation (REST/MCP API, escrow ledger, staking and
slashing logic, registry verification) and the official Pacta apps and website.

Out of scope: issues in third-party dependencies (report those upstream), and the
demo/reference deployments' lack of authentication or TLS, which are known limitations
of the current proof-of-concept and are documented as such.

## Note on the current stage

Pacta is an early proof of concept. The public demo runs without authentication and is
not intended to hold real funds or sensitive data. Please do not submit real personal
or financial information to demo instances.
